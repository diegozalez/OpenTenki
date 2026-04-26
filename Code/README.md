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

## Tasmota — Coming Soon

The board is compatible with Tasmota, but Tasmota does not yet fully support
the ESP32-S3, so some errors are still possible. The configuration is being
finalized and will be uploaded soon.

## Arduino — Coming Soon
