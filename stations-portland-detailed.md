# Portland Downtown EV Charging Stations — Detailed Data

> Auto-generated from OpenStreetMap (ODbL) and PlugShare. For use in EVMap, OCM, and other green transportation projects.

## Summary

- **Location**: Downtown Portland, OR (center: 45.5159, -122.6822)
- **Search radius**: 5 km
- **Total stations found**: 8+
- **Date mapped**: July 2026

---

## Station Details

### 1. Tesla Supercharger — 805 SW Broadway
- **Operator**: Tesla
- **Connector**: NACS (4 plugs)
- **Power**: 250 kW DC Fast
- **Access**: Tesla customers only
- **Distance from center**: ~317 m
- **Hours**: 24/7
- **Reference**: Tesla ref 15277
- **Tags**: `amenity=charging_station`, `brand=Tesla Supercharger`, `network=Supercharger`

### 2. Blink — SW Broadway area
- **Operator**: Blink
- **Connector**: J-1772
- **Power**: 7.2 kW Level 2
- **Access**: Public
- **Distance from center**: ~565 m
- **Capacity**: 4 ports
- **Tags**: `amenity=charging_station`, `brand=Blink`, `level=2`

### 3. Blink — SW Clay / Community Center area
- **Operator**: Blink
- **Connector**: J-1772
- **Power**: Level 2
- **Access**: Public
- **Distance from center**: ~624 m

### 4. Multi-Protocol Station
- **Operator**: Unknown
- **Connector**: J-1772 + CCS/SAE + CHAdeMO
- **Power**: DC Fast+
- **Access**: Public
- **Distance from center**: ~644 m
- **Tags**: `amenity=charging_station`, `socket:J-1772`, `socket:CCS`, `socket:CHAdeMO`

### 5. ChargePoint
- **Operator**: ChargePoint
- **Connector**: J-1772
- **Power**: Level 2
- **Access**: Public
- **Distance from center**: ~682 m
- **Tags**: `amenity=charging_station`, `brand=ChargePoint`

### 6. Blink — SW Aubrey St
- **Operator**: Blink
- **Connector**: J-1772
- **Power**: Level 2
- **Access**: Public
- **Distance from center**: ~735 m

### 7. Unnamed — Tesla/J-1772 adapter station
- **Operator**: Unknown
- **Connector**: Tesla:J-1772
- **Access**: Public
- **Distance from center**: ~242 m

### 8. Unnamed — Multi-protocol
- **Operator**: Unknown
- **Connector**: J-1772 + CCS + CHAdeMO
- **Access**: Public
- **Distance from center**: ~644 m

---

## Data Formats

### OCM-Compatible JSON
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
  ]
}
```

### GeoJSON Feature
```json
{
  "type": "Feature",
  "properties": {
    "name": "Tesla Supercharger",
    "operator": "Tesla",
    "power": "250kW",
    "connector": "NACS",
    "access": "customers"
  },
  "geometry": {
    "type": "Point",
    "coordinates": [-122.68045, 45.51844]
  }
}
```

---

**Data sources**: OpenStreetMap (ODbL), PlugShare. All data attributed per ODbL.