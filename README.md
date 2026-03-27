# OpenRoof Geometry Data

GeoJSON boundary files for the OpenRoof housing market map.

## Sources

- **ZIP (ZCTA)**: Census Bureau TIGER/Line 2023 — full resolution
- **Place/City**: Census Bureau TIGER/Line 2023 — incorporated places only (LSAD 25, 43, 47, 57)
- **County**: Census Bureau Cartographic Boundaries 2023
- **State**: Census Bureau Cartographic Boundaries 2023
- **Metro**: Census Bureau CBSA Boundaries 2023

## Structure

```
zip/[STATE].geojson      # ZIP code (ZCTA) polygons per state
place/[STATE].geojson    # City/town/village boundaries per state
county/[STATE].geojson   # County boundaries per state
state/                   # National state boundaries
metro/                   # National metro area boundaries
```

## License

Source data is from the U.S. Census Bureau and is in the public domain.
