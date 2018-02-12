[![ TMD2772](TMD2772_I2C.png)](https://store.ncd.io/product/tmd2772-digital-ambient-light-and-proximity-sensor-i2c-mini-module/).

#  TMD2772

Manufactured by AMS, the TMD2772 provides digital ambient light sensing (ALS), a complete proximity detection system, and digital interface logic.The ALS enhancements include a reduced-gain mode that extends the operating range in sunlight. Proximity detection includes improved signal-to-noise performance and more accurate factory calibration.
This Device is available from www.ncd.io 

[SKU: TMD2772]

(https://store.ncd.io/product/tmd2772-digital-ambient-light-and-proximity-sensor-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TMD2772 digital ambient light proximity sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tmd2772-digital-ambient-light-and-proximity-sensor-i2c-mini-module/">TMD2772 digital ambient light proximity sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TMD2772.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
