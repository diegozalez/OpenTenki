# OpenTenki on ESPHome

The [`opentenki-v2.yaml`](opentenki-v2.yaml) file can be uploaded to your
ESPHome builder. It's written to work with Home Assistant out of the box, but
it can also be used in MQTT-only mode.

> **Important:** before flashing, change the Home Assistant API encryption key
> and make sure your Wi-Fi credentials are configured (in `secrets.yaml` or
> directly in the file).

## How to use

1. In the ESPHome dashboard, create a new device.
2. Replace the generated configuration with the contents of
   [`opentenki-v2.yaml`](opentenki-v2.yaml).
3. Update `wifi_ssid` / `wifi_password` (in `secrets.yaml`) and the API
   encryption key.
4. Install the firmware over USB (first time) or OTA.
