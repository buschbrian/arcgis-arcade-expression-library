# ArcGIS Arcade Expression Library

A curated library of reusable Arcade expressions for ArcGIS Online, ArcGIS Pro, Field Maps, Dashboards, Experience Builder, pop-ups, labels, symbology, attribute rules, and data validation.

This repository focuses on expressions that are useful, reusable, and a little harder to write from scratch: related-record lookups, FeatureSet filtering, geometry logic, dashboard indicators, smart form calculations, attribute rules, and null-safe utilities.

## Why this exists

Arcade is powerful, but many real-world workflows require more than a one-line expression. This library gives GIS users a searchable place to find advanced examples, learn patterns, and adapt expressions for their own maps and apps.

## How to use this repo

Browse the `expressions/` folder by workflow:

- `popups/` - formatted pop-ups, related records, summaries, and conditional display
- `labels/` - advanced labels, multi-line labels, and fallback logic
- `symbology/` - data-driven symbol classes and visual logic
- `dashboards/` - indicators, list formatting, serial charts, and metrics
- `field-maps/` - smart forms, calculated values, and mobile editing helpers
- `attribute-rules/` - calculation, constraint, and validation patterns
- `data-validation/` - QA/QC checks and data quality expressions
- `geometry/` - distance, area, length, intersection, and spatial logic
- `dates-times/` - age, elapsed time, fiscal periods, and date formatting
- `related-records/` - related table lookups and aggregations
- `utilities/` - reusable helper patterns for nulls, domains, coded values, and text

Each expression includes:

- Use case
- Arcade profile
- Required fields or layers
- Expression code
- Example output
- Notes and limitations
- Tags

## Arcade profiles

Arcade expressions run in different profiles depending on where they are used. A function that works in a pop-up may not work in labeling, symbology, or attribute rules. Always check the listed profile before using an expression.

See [`docs/arcade-profiles.md`](docs/arcade-profiles.md) for profile notes.

## Starter examples

This repo currently includes examples for:

- Related record counts
- Related record summaries
- Conditional pop-up sections
- Null-safe labels
- Dashboard status indicators
- Field Maps smart form defaults
- Attribute rule calculations
- Data validation checks
- Geometry-based warnings
- Date and time calculations
- FeatureSet lookups
- Utility formatting patterns

## Contributing

Contributions are welcome. Please use [`templates/expression-template.md`](templates/expression-template.md) for new expressions and read [`CONTRIBUTING.md`](CONTRIBUTING.md) before opening a pull request.

## Disclaimer

These expressions are examples and starting points. Test expressions against your own schema, Arcade profile, ArcGIS version, and data before using them in production.

## License

MIT. See [`LICENSE`](LICENSE).
