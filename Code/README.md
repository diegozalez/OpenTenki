# OpenTenki Firmware

Here you can find all the firmware integrations for OpenTenki. In this project
it is very important to be as open and as compatible as possible, so if there
is a platform you would like covered (or that you can adapt OpenTenki to), let
me know — it will only make the project better.

## ESPHome / Home Assistant

The recommended path. The full implementation lives in
[`EspHome/opentenki-v2.yaml`](EspHome/opentenki-v2.yaml) and works great: every
sensor is exposed, the status LED is fully integrated, and pressing the
on-board button confirms connectivity to Home Assistant. The board can also
calculate indoor air quality (IAQ) through the BME688's BSEC2 stack.

## Tasmota

A working [basic template](Tasmota) is available: the BME688, HDC3022, user
button and LED work out of the box (the VEML7700 needs a custom-compiled
binary). Tasmota's ESP32-S3 support is still maturing, so expect some rough
edges — feedback is welcome.

## Arduino — Coming Soon
