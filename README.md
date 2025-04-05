# thermal-pilot

🧊 Smart Fan Control for SBC / STB Devices using GPIO + MOSFET

This script monitors CPU temperature and automatically controls a fan connected via MOSFET (e.g. IRFZ44N) through GPIO pin.

Tested on Amlogic S905X-BV (HG680P) running Armbian.

## Features
- Customizable temperature thresholds
- Logging via syslog (`logger -t FAN_MONITOR`)
- Fail-safe trap to keep fan ON on exit
- Compatible with systemd service

## Wiring
See schematic in `/docs` or hardware diagram.

## License
MIT
