# OpenTenki on Tasmota

With the basic template below you get the BME688, the HDC3022, the user button
and the LED working. The VEML7700 is **not** included by default — to enable it
you need to use a custom-compiled Tasmota binary.

## Basic Template

```json
{"NAME":"OpenTenki","GPIO":[32,1,1,640,608,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1376,0,0,0,0,1,1,1,1,1,1,1,1,1,1,1],"FLAG":0,"BASE":1}
```
