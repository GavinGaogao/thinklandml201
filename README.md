# thinklandml201

## About RPi package
Mock package RPi exists only for the purpose of generating pdoc. 
After deploying to your Thinkland Raspberry Pi Car, be sure to remove the mock package.

## API documentation
Look for *.m.html for each module

## Demos
### A cruising car avoiding obstacles using infrared+ultrasound
```python
from thinkland_rpi_car import Car
Car.demo_cruising()
```
### Line tracking mode
```python
from thinkland_rpi_car import Car
Car.demo_line_tracking(speed=50)
```
