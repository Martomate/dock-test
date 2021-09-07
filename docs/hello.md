---
title: Hello
---

## This is quality content

```python:title=sleep.py
import asyncio
from cowait import task

@task
async def Sleep(duration: int = 5):
    for i in range(duration):
      await asyncio.sleep(1) # blocking
      print("slept", i + 1)

    return {
        "duration": duration,
    }
```

awdawdawdawd
