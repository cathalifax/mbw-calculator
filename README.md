# MBW Shipping Calculator

Password-protected internal tool for Convenient Auto & Tire (Halifax) staff.

- `index.html` – the tire shipping calculator, encrypted with [StatiCrypt](https://github.com/robinmoisson/staticrypt). Ask the shop for the staff password.
- `inventory/index.html` – Tire Bin Transfers (Prospect bins 11–40 ⇄ Spryfield bins 1–10), encrypted the same way with the same staff password. Records moves and prepares a TireGuru update queue; it does not change TireGuru.
- `fuel.json` – MBW Courier's current fuel surcharge (source: https://www.mbwcourier.ca/fuel-surcharges). Updated weekly; the calculator loads it automatically.
