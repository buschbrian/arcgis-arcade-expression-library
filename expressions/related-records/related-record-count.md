# Related Record Count

## Use case

Display the number of related inspections, work orders, permits, or other child records connected to the current feature.

## Arcade profile

Popup

## Required fields, layers, or relationships

- A relationship class between this layer and the related table (named `Inspections` in this example)

## Expression

```js
var related = FeatureSetByRelationshipName($feature, 'Inspections');
return Count(related);
```

## Example output

```text
12
```

## Notes

Replace `Inspections` with your relationship name.

## Tags

`arcade`, `related-records`, `popup`, `featureset`
