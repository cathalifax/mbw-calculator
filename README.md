# Convenient Auto & Tire – staff site

Password-protected internal tools for Convenient Auto & Tire (Halifax) staff, encrypted with
[StatiCrypt](https://github.com/robinmoisson/staticrypt). Sign in with your username (Erdet, Ermal or Liri)
and the staff password; one sign-in opens every page.

- `index.html` – home page: **MBW Shipping** and **Tire Management** buttons, signed-in name, Sign out.
- `mbw/index.html` – MBW Courier tire shipping calculator + "Book with MBW" (moved here from the site root on Oct 4, 2026;
  old root links with a prefilled quote, e.g. `/?pl=4&town=…`, are forwarded here).
- `inventory/index.html` – Tire Management: tire bin transfers Prospect (bins 11–40) ⇄ Spryfield (bins 1–10), stock and a
  TireGuru update queue. It does not change TireGuru.
- `fuel.json` – MBW Courier's current fuel surcharge (source: https://www.mbwcourier.ca/fuel-surcharges). Stays at the site root;
  updated weekly; the calculator loads it automatically.
