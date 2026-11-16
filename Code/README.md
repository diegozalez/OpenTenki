# OpenTenki Firmware

Here you can find the firmware integrations for OpenTenki. ESPHome is the
officially supported path; Tasmota and Arduino are possible too, and since the
hardware is fully open, you are welcome to adapt OpenTenki to any platform you
like.

## ESPHome / Home Assistant — supported

The recommended and officially supported path. The full implementation lives in
[`EspHome/opentenki-v2.yaml`](EspHome/opentenki-v2.yaml) and works great: every
sensor is exposed, the status LED is fully integrated, and pressing the
on-board button confirms connectivity to Home Assistant. The board can also
calculate indoor air quality (IAQ) through the BME688's BSEC2 stack.

## Tasmota — community

The board also runs on Tasmota. A working [basic template](Tasmota) is provided
to get you started (BME688, HDC3022, user button and LED work out of the box;
the VEML7700 needs a custom-compiled binary). This path is not actively
maintained, but contributions are welcome.

## Arduino — community

OpenTenki uses a standard ESP32-S3, so it works with the Arduino framework as
well. There is no reference sketch yet, but community contributions are very
welcome.
