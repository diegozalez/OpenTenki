# OpenTenki 🚧 Construction in progress 🚧

<table>
  <tr>
    <td valign="middle" width="50%">
      <img src="Media/CajaShow.png" width="1000" alt="OpenTenki weather station">
    </td>
    <td valign="middle">
      OpenTenki is an open-source, affordable, and precise indoor weather station
      hardware platform built around an ESP32-S3 mini and multiple environmental
      sensors. It is designed for hobbyists and is compatible with ESPHome and
      Tasmota firmware, enabling easy integration with home automation systems
      via MQTT or Matter.
    </td>
  </tr>
</table>

## Features

<table>
  <tr>
    <td valign="middle">
      <ul>
        <li>Accurate environmental sensing with:
          <ul>
            <li>VEML7700 (ambient light, infrared and full-spectrum light)</li>
            <li>BME688 (temperature, humidity, pressure, air quality)</li>
            <li>HDC3022 (high-precision temperature and humidity)</li>
            <li>WS2812C (NeoPixel) status LED</li>
            <li>User button for control and feedback</li>
          </ul>
        </li>
        <li>Based on the ESP32-S3 mini for robust Wi-Fi and Bluetooth connectivity</li>
        <li>Fully open-source hardware and software</li>
        <li>Designed for easy customization and extension</li>
        <li>Supports MQTT and Matter protocols for data transmission</li>
      </ul>
    </td>
    <td valign="middle" width="50%">
      <img src="Media/CajaCable.jpg" width="1000" alt="OpenTenki assembled, powered over USB-C">
    </td>
  </tr>
</table>

---

## Repository Structure

- [`PCB/`](PCB) — Schematic, Gerber files, BOM, EasyEDA project and PCB renders
- [`Code/`](Code) — Firmware integrations (ESPHome, Tasmota, more coming)
- [`Case3D/`](Case3D) — 3D-printable case files
- [`Media/`](Media) — Photos and renders of the board and case

---

## Getting Started

### Hardware

<table>
  <tr>
    <td valign="middle" width="50%">
      <img src="Media/FrontPCBT.png" width="1000" alt="OpenTenki PCB render">
    </td>
    <td valign="middle">
      <ul>
        <li>Order the PCB with the <a href="PCB/Gerber_PCB2_2026-04-26">Gerber files</a>
          and the <a href="PCB/BOM_OpenTenki_PCB2_2026-07-24.xlsx">BOM</a> — see the
          <a href="PCB">PCB folder</a> for the schematic, the interactive BOM and the
          full EasyEDA project.</li>
        <li>3D-print the <a href="Case3D">case</a>: three printed parts and one screw.</li>
      </ul>
    </td>
  </tr>
</table>

### Firmware

- Compatible with [ESPHome](https://esphome.io/) and
  [Tasmota](https://tasmota.github.io/) out of the box.
- Custom firmware (Arduino, etc.) is in development — contributions welcome!

### Usage

1. Flash ESPHome or Tasmota firmware configured for OpenTenki sensors
   (see [`Code/EspHome/`](Code/EspHome) for a ready-to-use YAML).
2. Connect the board to power and Wi-Fi.
3. Integrate the sensor data with your home automation platform via MQTT or Matter.

---

## Contributing

Contributions, bug reports and feature requests are more than welcome! Please
open an issue or a pull request on GitHub.

---

## License

OpenTenki is licensed under the Apache License 2.0. See [LICENSE](LICENSE) for
details.

---

## Contact

For questions or discussions, open an issue or contact diegozalezz@gmail.com.
