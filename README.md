# Portland ↔ Beaverton EV Commute Mapping Project

Open-source green transportation mapping: EV charging stations, bike/walk commute analysis, and sustainable transit data for the Portland ↔ Beaverton corridor.

## 📍 Corridor Overview

| Detail | Value |
|---|---|
| **Origin** | Downtown Portland, OR (45.5159, -122.6789) |
| **Destination** | Beaverton, OR (45.4872, -122.8038) |
| **Distance** | ~12.8 km (8 miles) |
| **Primary Route** | Sunset Highway (US-26) / Beaverton-Tigard Freeway |
| **Alternative Modes** | EV, Bike, Bus/Transit |

## 🔋 EV Charging Stations

### Downtown Portland (5 km radius — 11 stations)
See [stations-portland.json](stations-portland.json) for complete data.

| Station | Operator | Connector | Power | Access | Distance |
|---------|----------|-----------|-------|--------|----------|
| Tesla Supercharger | Tesla | NACS | 250 kW DC Fast | Customers only | ~317 m |
| Multi-Protocol | Unknown | J-1772 + CCS + CHAdeMO | DC Fast+ | Public | ~644 m |
| Blink (#1) | Blink | J-1772 | L2 | Public | ~565 m |
| Blink (#2) | Blink | J-1772 | L2 | Public | ~624 m |
| Blink (#3) | Blink | J-1772 | L2 | Public | ~735 m |
| ChargePoint | ChargePoint | J-1772 | L2 | Public | ~682 m |

### Beaverton (5 km radius — 7 stations)
See [stations-beaverton.json](stations-beaverton.json) for complete data.

| Station | Operator | Connector | Power | Access |
|---------|----------|-----------|-------|--------|
| ChargePoint (Walmart) | ChargePoint | J-1772 | L2 | Public |
| Multi-Protocol | Unknown | J-1772 + CCS + CHAdeMO | Unknown | Public |
| Blink | Blink | J-1772 | L2 | Public |
| Electrify America | EA | CCS + CHAdeMO | 50–350 kW DC Fast | Public |

## 🚴 Commute Mode Analysis

| Mode | Duration | Feasibility | CO₂ Impact |
|---|---|---|---|
| 🚗 EV | 15–20 min | ✅ Best sustainable choice | ~0.6 kg (vs ~2.6 kg gas) |
| 🚌 Transit | 35–50 min | ✅ Good alternative | ~0.9 kg |
| 🚴 Bike | 25–40 min | ⚠️ Borderline (Sunset Hwy barrier) | Zero |
| 🚶 Walk | 2.5–3 hrs | ❌ Not practical | Zero |

## 📁 Data Files

- `stations-portland.json` — Complete Portland downtown station data
- `stations-beaverton.json` — Complete Beaverton station data
- `commute-analysis.md` — Full sustainability analysis

## 🌱 How to Contribute

1. Verify/improve station data with field surveys
2. Add new stations as chargers expand
3. Submit bike/walk route improvements
4. Share with the Open Charge Map community

## 📜 License

Data is contributed under Open Database License (ODbL). Please attribute OSM contributors.

## 🔗 Related Projects

- [Open Charge Map](https://openchargemap.org) — Global EV charging station registry
- [ev-map/EVMap](https://github.com/ev-map/EVMap) — Android EV charging station finder (267 stars)
- [openchargemap/ocm-app](https://github.com/openchargemap/ocm-app) — OCM web & mobile app