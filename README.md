# Kerala Open Maps

A comprehensive collection of open geographic boundary data for Kerala — covering administrative, electoral, and local governance layers. Sourced from LGD, ECI, OSM, and Delimitation Commission of Kerala. Available under the Open Database License (ODbL).

## Layers

| Layer | Source | Features |
|---|---|---|
| State Boundary | LGD | 1 |
| Districts | LGD | 14 |
| Sub-Districts | LGD | 76 |
| Blocks | LGD | 152 |
| Parliamentary Constituencies | LGD / ECI | 20 |
| Assembly Constituencies | LGD / ECI | 141 |
| LSG (Panchayat/Municipality/Corporation) | OpenStreetMap Kerala | 1,035 |
| Wards | [Vonter/kerala-wards](https://github.com/Vonter/kerala-wards) | ~21,000 |
| Villages | LGD | 1,623 |

## Data Sources

- [Local Government Directory (LGD)](https://lgdirectory.gov.in) — Government of India
- [Election Commission of India (ECI)](https://eci.gov.in)
- [OpenStreetMap Kerala Community](https://openstreetmap.org)
- [Delimitation Commission Kerala / wardmap.ksmart.live](https://wardmap.ksmart.live)

## License

All data is made available under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/).

You are free to share and adapt the data as long as you:
- Attribute this project
- Share any adaptations under the same license

## Attribution

If you use this data, please attribute as:
> Kerala Open Maps — https://github.com/medonthomas-alt/Kerala_Open_Maps — ODbL License

## Contributing

Found an error? Have better data? Open an issue or send a pull request.


## Changelog

### v1.1 — March 2026
- Added ward boundaries for all 14 districts (~21,000 wards)
- Wards split by district for better performance (14 separate files)
- Ward boundaries sourced from Delimitation Commission Kerala (2024)
- Ward labels visible at zoom level 13+
- Fixed layer toggle functionality
- Added zoom-based label visibility for all layers

### v1.0 — March 2026
**Initial release**
- State boundary (LGD)
- Districts — 14 (LGD)
- Sub-Districts — 76 (LGD)
- Blocks — 152 (LGD)
- Parliamentary Constituencies — 20 (LGD/ECI)
- Assembly Constituencies — 141 (LGD/ECI)
- LSG Bodies — 1,035 (OpenStreetMap Kerala)
- Villages — 1,623 (LGD)
- Interactive map viewer with layer toggles
- Click-to-inspect popups
- Search functionality
- Zoom-based label visibility

## Known Issues
- LSG boundaries (OpenStreetMap, 2020) and ward boundaries (Delimitation Commission, 2024) are from different sources and may not perfectly align at boundaries
- Village names use 2011 census names — some may differ from current local usage
- Data is intended for research and visualization purposes, not for legal or administrative use
