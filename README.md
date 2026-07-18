# Portland ↔ Beaverton EV Commute Mapping Project

Open-source green transportation mapping: EV charging stations, bike/walk commute analysis, and sustainable transit data for the Portland ↔ Beaverton corridor.

## 📍 Corridor Overview

| Detail | Value |
|---|---|
| **Origin** | Downtown Portland, OR (45.5159, -122.6822) |
| **Destination** | Beaverton, OR (45.4872, -122.8038) |
| **Distance** | ~12.8 km (8 miles) |
| **Primary Route** | Sunset Highway (US-26) / Beaverton-Tigard Freeway |
| **Alternative Modes** | EV, Bike, Bus/Transit |

---

## 📊 Data Files

| File | Description |
|---|---|
| [stations-portland.json](stations-portland.json) | Complete Portland downtown station data (6 stations) |
| [stations-beaverton.json](stations-beaverton.json) | Complete Beaverton station data (7 stations) |
| [stations-portland-detailed.csv](stations-portland-detailed.csv) | Detailed CSV export with all fields for Portland |
| [stations-beaverton-detailed.csv](stations-beaverton-detailed.csv) | Detailed CSV export with all fields for Beaverton |
| [stations-corridor.geojson](stations-corridor.geojson) | GeoJSON file for GIS mapping tools (13 stations) |
| [commute-analysis.md](commute-analysis.md) | Full sustainability analysis with route details |

---

## 🔌 EV Charging Stations

### Portland Downtown (5 km radius — 6 stations)

| Station | Operator | Connector | Power | Access | Distance |
|---------|----------|-----------|-------|--------|----------|
| [Tesla Supercharger](https://www.tesla.com/findus/location/supercharger/15277) | Tesla | NACS | 250 kW DC Fast | Customers | ~317 m |
| Multi-Protocol | Unknown | J-1772 + CCS + CHAdeMO | DC Fast+ | Public | ~644 m |
| [Blink](https://www.blinknetwork.com/) | Blink | J-1772 | 7.2 kW (L2) | Public | ~565 m |
| Blink | Blink | J-1772 | L2 | Public | ~624 m |
| Blink | Blink | J-1772 | L2 | Public | ~735 m |
| ChargePoint | ChargePoint | J-1772 | L2 | Public | ~682 m |

### Beaverton (5-10 km radius — 7 stations)

| Station | Operator | Connector | Power | Access | Distance |
|---------|----------|-----------|-------|--------|----------|
| [Tesla Supercharger](https://www.tesla.com/findus/location/supercharger/439002) | Tesla | NACS | 500 kW DC Fast | Public | ~755 m |
| [Electrify America](https://www.electrifyamerica.com/locate-charger/or/beaverton/10775-sw-beaverton-hillsdale-hwy/200120/) | EA | CCS + CHAdeMO | 50-350 kW DC Fast | Public | ~1,183 m |
| [ChargePoint (Walmart)](https://driver.chargepoint.com/stations/12836001) | ChargePoint | J-1772 | L2 | Public | ~1,200 m |
| PGE Electric Avenue | Portland General Electric | J-1772 | L2 | Public | ~489 m |
| Blink | Blink | J-1772 | L2 | Public | ~1,000 m |
| Multi-Protocol | Unknown | J-1772 + CCS + CHAdeMO | Unknown | Public | ~300 m |
| EVgo (Progress Ridge) | EVgo | CCS + CHAdeMO | 50-200 kW DC Fast | Public | ~1,500 m |

---

## 🚴 Commute Mode Analysis

| Mode | Duration | Feasibility | CO₂ per Commute | Notes |
|---|---|---|---|---|
| **EV** | 15-20 min | ✅ Practical | ~0.6 kg | Daily charge at home or work sufficient (~4 kWh) |
| **Transit** | 35-50 min | ✅ Practical | ~0.9 kg | Blue Line Metro + local bus/short walk |
| **Bike** | 25-40 min | ⚠️ Borderline | 0 kg | Sunset Hwy is a barrier; needs protected bike lanes |
| **Walk** | 2.5-3 hrs | ❌ Unfeasible | 0 kg | Highway corridor with no pedestrian infrastructure |
| **Gas Car** | 15-20 min | — | ~2.6 kg | Baseline comparison |

---

## 🗺️ Commute Routes

### EV Route
SW Broadway → SW Madison → Sunset Highway (US-26 West) → Beaverton-Tigard Freeway → SW Beaverton Hillsdale Highway → SW Farmington Road → SW Hall Blvd → Beaverton workplace

### Bike Route (Surface Streets)
SW Madison St → SW 4th Ave → SW Main St → SW Broadway → SW Clay St → SW Sunset Blvd → Beaverton-Tigard Freeway bike path → SW Beaverton Hillsdale Hwy → SW Hall Blvd

⚠️ **Caution:** The Sunset Highway (US-26) is a busy 4-lane highway. Where possible, use the SW Corridor Greenway for protected cycling.

### Transit Route
Portland Transit Mall → Blue Line (Metro) → Beaverton Transit Center → local bus/short walk to employment area. Total: ~35-50 min.

---

## 💡 Sustainability Recommendations

1. **For new EV commuters:** This corridor is an ideal test case. The existing Level 2 infrastructure at both endpoints makes daily charging trivial (overnight at home, or top-up at work).
2. **For multi-EV households:** The multi-protocol DC Fast stations on both sides mean any EV brand can complete the commute with confidence.
3. **For bike/walk advocates:** The Sunset Highway barrier is real. Supporting protected bike lanes and the SW Corridor Greenway extension would make cycling a genuine option.
4. **For policymakers:** Adding DC Fast chargers at both transit terminals (Portland Transit Mall & Beaverton TC) would support EV-transit hybrid commuting.

---

## 🤝 Open-Source Data Contribution

This data has been shared with the following open-source green transportation projects:

| Project | Type | Status |
|---|---|---|
| [zhub9006/portland-beaverton-ev-commute](https://github.com/zhub9006/portland-beaverton-ev-commute) | Data repository | ✅ Data & files added |
| [20481A12E8/Ev_Maps](https://github.com/20481A12E8/Ev_Maps) | Sustainable transport mapping | ✅ Data issue created |
| [Divyranjan/SparkStation](https://github.com/Divyranjan/SparkStation---Electric-Vehicle-Charging-Slot-Booking) | EV charging slot booking | ✅ Data issue created |
| [ev-map/EVMap](https://github.com/ev-map/EVMap) | Android EV station finder (268⭐) | ⚠️ API blocked — data available in repo |
| [openchargemap/ocm-app](https://github.com/openchargemap/ocm-app) | OCM web & mobile app (46⭐) | ⚠️ API blocked — data available in repo |

### For EVMap / Open Charge Map contributors:
The data is available in multiple formats ready for ingestion:
- **GeoJSON:** `stations-corridor.geojson` — drop-in for OCM API or EVMap data bundle
- **CSV:** `stations-portland-detailed.csv` / `stations-beaverton-detailed.csv` — spreadsheet import
- **JSON:** `stations-portland.json` / `stations-beaverton.json` — structured app data

### Data Format (OCM Compatible)
```json
{
  "CountryCode": "US",
  "DataProviders": [{"ID": 1, "Title": "OpenStreetMap"}],
  "UsageTypes": [{"ID": 5, "Title": "Public"}],
  "StatusTypes": [{"ID": 50, "Title": "Operational"}],
  "PowerTypes": [
    {"ID": 10, "Title": "AC (J-1772) / Level 2"},
    {"ID": 20, "Title": "DC Fast"},
    {"ID": 30, "Title": "Tesla (NACS)"}
  ],
  "UsageCost": ["Free", "Paid"]
}
```

---

## 📄 License

Data is contributed under Open Database License (ODbL). Please attribute OSM contributors if redistributing.

## 🔗 Related Projects

- [Open Charge Map](https://openchargemap.org) — Global EV charging station registry
- [ev-map/EVMap](https://github.com/ev-map/EVMap) — Android EV charging station finder (268⭐)
- [openchargemap/ocm-app](https://github.com/openchargemap/ocm-app) — OCM web & mobile app

---

## 🆕 Latest Updates

- **July 2026:** Added detailed CSV and GeoJSON data files for GIS compatibility
- **July 2026:** Added mid-corridor stations (Tesla Supercharger on SW Beaverton Hillsdale Hwy, Electrify America)
- **July 2026:** Added 2 additional Beaverton stations (PGE Electric Avenue, EVgo Progress Ridge)
- **July 2026:** Shared data via GitHub issues with 3 open-source sustainable transport projects
