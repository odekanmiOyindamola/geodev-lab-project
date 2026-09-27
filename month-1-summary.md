# Month 1 Summary

## Question

How are low-lying settlements distributed across the Lokoja A-E
wards, and which wards contain more low-lying settlements that may
be relevant to flood-risk assessment?

## Spatial Operation

I used the Count Points in Polygon operation.

The Lokoja A-E ward polygons were used as the polygon layer, while
the low-lying settlement points were used as the point layer.

The operation was performed using projected data in EPSG:32632
(WGS 84 / UTM Zone 32N).

## Why I Chose This Operation

Count Points in Polygon was selected because it allows me to quantify
the number of low-lying settlement points within each Lokoja ward.
This provides an initial spatial indication of how settlements that
may be relevant to flood-risk assessment are distributed across the
study area.

## What I Expected

Before running the operation, I expected approximately:

- Lokoja A: [your estimate]
- Lokoja B: [your estimate]
- Lokoja C: [your estimate]
- Lokoja D: [your estimate]
- Lokoja E: [your estimate]

I expected the total number of points within the five wards to be
approximately [your estimate].

## What I Got

The actual results were:

- Lokoja A: [actual result]
- Lokoja B: [actual result]
- Lokoja C: [actual result]
- Lokoja D: [actual result]
- Lokoja E: [actual result]

Total counted points: [actual total]

## Validation

I checked the result in four ways:

1. I inspected the result on the map to confirm that the spatial
   distribution of points and ward boundaries was sensible.
2. I compared the resulting point count with the expected number of
   points.
3. I manually verified at least one ward to confirm that the
   calculated count corresponded with the settlement points visible
   within the ward.
4. I checked the resulting geometry for empty or invalid geometries.

## What Surprised Me

[Write what actually surprised you after seeing the result.]

For example:

I expected the low-lying settlements to be relatively evenly
distributed across the five wards, but the results showed a more
uneven distribution than I anticipated.

## What Data I Still Need

The analysis provides a count of low-lying settlement points by ward,
but additional data are still required for a more complete flood-risk
assessment. These may include river/waterway data, elevation data,
historical flood information, rainfall data, river-gauge or
water-level observations, and other relevant exposure or
vulnerability data.
