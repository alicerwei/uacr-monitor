# uACR Monitor

Automated dipstick color analysis dashboard for kidney health monitoring.
Built for BME 4090 — Cornell University.

## Pages
- `index.html` — Patient login
- `dashboard.html` — uACR history, chart, and reading log

## uACR Estimation Note
uACR is currently estimated using a placeholder ratio of pad1R / pad2R × 30.
This scaling factor will be updated once RGB-to-concentration calibration is complete.

## Data Storage
Readings are stored in the browser's localStorage.
Once Flask integration with the Raspberry Pi is complete, data will be pushed automatically from colordetect2.py.
