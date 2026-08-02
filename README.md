# UK/NI → Ireland Car Import Cost Calculator

A free tool that estimates the full cost of importing a used car from the UK (Great Britain **or** Northern Ireland) into the Republic of Ireland.

## Features

- **GBP → EUR** conversion using a live exchange rate (with a built-in default fallback)
- **Paste a listing link** — drop in an Autotrader, cars.ni, DoneDeal or similar URL and the app auto-fills make, model, year, price and origin from the page (falls back to reading the link itself)
- **GB vs Northern Ireland** distinction — NI cars pay no customs duty or import VAT
- **Private buyer vs VAT-registered dealer** — dealers can reclaim import VAT
- **VRT (Vehicle Registration Tax)** using Revenue's Category A CO₂ bands (2022+), including the minimum-VRT rule for low-value cars
- **NOx levy** (tiered per mg/km)
- **EV VRT relief** (up to €5,000 for OMSP ≤ €40k, registrations before 31 Dec 2026)
- **Customs duty** (10% GB) and **import VAT** (23% GB)
- Registration fee, NCT, and shipping costs
- **Annual motor tax estimate** by CO₂ band (2021+ rates)
- Runs fully in your browser — no data is sent to any server

## How to use

1. **Optional:** paste a link to a car for sale (Autotrader UK, cars.ni, DoneDeal…) and hit **Extract details** — the form fills itself
2. Enter the make, model, year of first registration, and UK purchase price
3. Enter the CO₂ figure (g/km) from the V5C — this drives VRT and motor tax
4. Enter the NOx figure if known (from Revenue's NOx calculator / V5C)
5. Select **Great Britain** or **Northern Ireland** as the car's origin
6. Select **private buyer** or **VAT-registered dealer**
7. Hit **Calculate** — you get a full breakdown in EUR

> **Important:** This is an estimate. Final duty, VAT and VRT are set by Revenue at registration. VRT is based on Revenue's OMSP (Open Market Selling Price), which we approximate as UK price + shipping + duty.

## Privacy

The calculator runs entirely in your browser. The only external requests are the public open.er-api.com exchange-rate API and — only when you use *Extract details* — the listing page itself via a public CORS proxy. No personal data is sent anywhere.

## Disclaimer

Not financial or legal advice. Always confirm the exact figures with Revenue (revenue.ie) or a customs broker before committing to a purchase.
