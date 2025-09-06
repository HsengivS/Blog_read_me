| Usage | Code Example | Real World Example | Behavior |
|-------|--------------|-------------------|----------|
| Without Await | `oven_on()` | Booking but not confirming | Just returns coroutine object |
| With Await | `await oven_on()` | Waiting at restaurant for the food | Runs & waits for result |
| With create_task | `asyncio.create_task(oven_on())` | Delivery order background process | Schedules run, doesn't wait |
