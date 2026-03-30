# Solar + EV Integration Sizing API

**The only API that correctly co-sizes solar and EV charging together.**  
Most solar calculators ignore EV load. Most EV calculators ignore solar. This models both correctly.

[![RapidAPI](https://img.shields.io/badge/RapidAPI-Subscribe-0055DA?style=flat-square)](https://rapidapi.com/bethelnedi/api/solar-ev-integration-sizing-api)
[![Docs](https://img.shields.io/badge/API_Docs-Swagger-85EA2D?style=flat-square)](https://amfumu-solar-ev-api.hf.space/docs)

## What a Single Call Returns
- EV annual electricity consumption (EPA fueleconomy.gov 2024 — 17 vehicles)
- Combined solar system size (PVWatts V8 — NREL/TP-6A20-62641)
- Extra panels and cost needed for EV load
- TOU charging cost comparison (State PUC rate filings 2024)
- Solar self-charging savings (NREL Solar+EV study 2023)
- V2H backup power assessment (Ford/Nissan/Rivian specs)
- Battery storage recommendation (NEM policy + EV load analysis)
- Full 25-year financial model

## EV Database (17 vehicles)
Tesla Model Y/3 · Ford F-150 Lightning · Chevy Equinox/Bolt · Hyundai Ioniq 6 · Kia EV6 · Rivian R1T · BMW i4 · VW ID.4 · Nissan LEAF Plus · Lucid Air Pure

## V2H Vehicles
Ford F-150 Lightning (9.6 kW, 78–104 kWh) · Rivian R1T (11.5 kW) · Nissan LEAF Plus (V2G capable)

## Plans
| Plan | Price | Calls |
|------|-------|-------|
| Free | $0/mo | 5/min — quick sizing |
| Pro | $49/mo | 1,000/hr — full 25-yr model |
| Bundle | $149/mo | All 5 Solar APIs |

## Topics
`solar-ev` `ev-charging` `tou-arbitrage` `v2h` `vehicle-to-home` `solar-sizing` `electric-vehicle` `nem` `pvwatts` `epa-efficiency` `v2g` `home-energy` `tesla` `ford-lightning` `fastapi` `python` `rapidapi`

---
