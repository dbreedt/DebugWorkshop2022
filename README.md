# DebugWorkshop2022

## The loop
* Gather
* Verify
* Fix
* Test

### Part 1 - Printf Debugging
Here we have a program that implements the formula to calculate `m=f*g` where `f` is the Discworld Value of π multiplied by the magical field's constant velocity and `g` is the cuberoot of 64 multiplied by the very made up fudge factor.

https://go.dev/play/p/9MY6RqSJhm-

Expecting result: 42

### Part 2 - Printf Debugging 2
Here we have a simple implementation of a sequential chunk total adder. It uses `s` the chunk summer, that calculates the total value of all the values in an array. Where `x` is the sum of a sequential chunk and `y` is the sum of a sequential chunk.

https://go.dev/play/p/kcomvCC1FSa

Expecting result: 81

### Part 3 - Breakpoints
Here we have the normal WeatherForecast web api, it has a bug, the value of temps seem to be wrong.

https://github.com/dbreedt/DebugWorkshop2022-1

### Part 4 - Breakpoints are my life now
Here we have the normal WeatherForecast web api, it however doesn't respond to my filter attempts. If I say `curl localhost:5000/weatherforecast/2` I want to receive 2 results, I just get a crash and burn currently.

https://github.com/dbreedt/DebugWorkshop2022-2

### Part 5 - Tests
Here we have the normal WeatherForecast web api, it doesn't increase sequential temps by 0.1°C.
Example:
```
Temp 0: 20
Temp 1: 20.1
Temp 2: 20.2
Temp 3: 20.3
...
```
use unit tests to help you debug.

https://github.com/dbreedt/DebugWorkshop2022-3