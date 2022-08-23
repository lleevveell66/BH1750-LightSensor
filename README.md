# BH1750_LightLevel
by LEVEL6 (https://github.com/lleevveell66)

### Purpose:

This simple python script will read data from a BH1750 light
sensor module on a Raspberry Pi and report back the value in lux.

### Connections:
 
```
 BH1750:                  RPi:
 ------                   ---
 Vcc                      3v3 (pin 1)
 GND                      GND (pin 9)
 SCL                      GPIO2/I2C1 SCL (pin 5)
 SDA                      GPIO3/I2C1 SDA (pin 3)
 ADDR                     X (no connection)
```

