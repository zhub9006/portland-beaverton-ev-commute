# Beaverton EV Charging Stations — Detailed Data

> Auto-generated from OpenStreetMap (ODbL) and PlugShare. For use in EVMap, OCM, and other green transportation projects.

## Summary

- **Location**: Beaverton, OR (center: 45.4872, -122.8038)
- **Search radius**: 10 km
- **Total stations found**: 9+
- **Date mapped**: July 2026

---

## Station Details

### 1. Blink — SW Broadway area
- **Operator**: Blink
- **Connector**: J-1772
- **Power**: Level 2
- **Access**: Public
- **Distance from center**: ~293 m
- **Capacity**: 3 ports

### 2. PGE Electric Avenue — Beaverton
- **Operator**: Portland General Electric
- **Connector**: J-1772
- **Power**: Level 2
- **Access**: Public
- **Distance from center**: ~489 m
- **Max stay**: 2 hours
- **Reference**: AFD ref 353901/353994/353995/353992/353991
- **Tags**: `amenity=charging_station`, `operator=Portland General Electric`

### 3. ChargePoint (Walmart)
- **Operator**: ChargePoint
- **Connector**: J-1772
- **Power**: Level 2
- **Access**: Public
- **Distance from center**: ~558 m
- **Reference**: PlugShare ref 207775
- **Tags**: `amenity=charging_station`, `brand=ChargePoint`

### 4. Tesla Supercharger — 11425 SW Beaverton Hillsdale Hwy
- **Operator**: Tesla
- **Connector**: NACS (16 plugs)
- **Power**: 500 kW DC Fast
- **Access**: Public (non-Teslas can charge with NACS adapter)
- **Distance from center**: ~755 m
- **Hours**: 24/7
- **Host**: Fred Meyer
- **Reference**: Tesla ref 439002, Supercharge.info ref 10227
- **Tags**: `amenity=charging_station`, `brand=Tesla Supercharger`, `network=Supercharger`
- **⚠️ Important**: Explicitly supports non-Tesla vehicles via NACS receptacle or adapter.

### 5. Blink — SW Century Blvd
- **Operator**: Blink
- **Connector**: J-1772
- **Power**: Level 2
- **Access**: Public
- **Distance from center**: ~959 m
- **Capacity**: 2 ports

### 6. Multi-Protocol Station
- **Operator**: Unknown
- **Connector**: J-1772 + CCS + CHAdeMO
- **Power**: Unknown
- **Access**: Public
- **Distance from center**: ~300 m

### 7. Electrify America — 10775 SW Beaverton Hillsdale Hwy
- **Operator**: Electrify America
- **Connector**: CCS (3 plugs) + CHAdeMO (1 plug)
- **Power**: 50–350 kW DC Fast (60 kW typical)
- **Access**: Public
- **Distance from center**: ~1,183 m
- **Hours**: 24/7
- **Reference**: PlugShare ref 301745, AFDC ref 183554
- **Tags**: `amenity=charging_station`, `brand=Electrify America`

### 8. EVgo — Progress Ridge
- **Operator**: EVgo
- **Connector**: CCS + CHAdeMO
- **Power**: 50–200 kW DC Fast
- **Access**: Public
- **Distance from center**: ~1,500 m

### 9. Tesla Supercharger — 3205 SW Cedar Hills Blvd
- **Operator**: Tesla
- **Connector**: NACS (12 plugs)
- **Power**: 250 kW DC Fast
- **Access**: Customers
- **Distance from center**: ~1,605 m
- **Hours**: 24/7
- **Covered**: Yes
- **Reference**: Tesla ref 26873, Supercharge.info ref 5541
- **Tags**: `amenity=charging_station`, `brand=Tesla Supercharger`, `network=Supercharger`

---

## Data Formats (OCM-Compatible)

### GeoJSON Feature Example (Electrify America)
```json
{
  "type": "Feature",
  "properties": {
    "name": "Electrify America",
    "operator": "Electrify America",
    "power": "50-350kW",
    "connector": "CCS+CHAdeMO",
    "access": "public"
  },
  "geometry": {
    "type": "Point",
    "coordinates": [-122.788612, 45.486910]
  }
}
```

---

**Data sources**: OpenStreetMap (ODbL), PlugShare. All data attributed per ODbL.