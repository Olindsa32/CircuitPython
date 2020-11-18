# CircuitPython
Repository for the Circuit Python module in Engineering 3

## Hello CircuitPython

### Description and Code

Thiss assignment is to get the neopixel to blink green and red and have it output to a serial monitor, "Make it Green" "Make it Red" based on the color it is switching to. you use the dot.fill command to change it to a color but instead of using built-in-colors, i=they instead use the number of red, green and blue on a scale from 0 to 255 for all. To space out the switches you use time.sleep and set it to a certain amount of seconds. To create the infinite loop needed on this assignment you have to create a while true and leave it without any parameter that needs to be filled, that makes it an endless loop.

### Evidence

``` python
import board
import neopixel
import time

dot = neopixel.Neopixel(board.NEOPIXEL, 1)


while True:
  print("Make it green!")
  dot.fill((0,255,0))
  time.sleep(.5)
  print("Make it red!")
  dot.fill((255 ,0,0))
  time.sleep(.5)
```

### Images

### Reflection

## CircuitPython Servo

### Description and Code

### Evidence

### Images

### Reflection

## CircuitPython LCD

### Description and Code

### Evidence

### Images

### Reflection
