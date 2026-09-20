# Data notes
## GRID3 Nigeria Operational Wards v3.0
Source: https://data.grid3.org
Downloaded: July 2026
5,872 features, Polygons
Columns: ward_name (Lokoja ward A- E), lga_name (Lokoja), State (Kogi)
Nulls is present
Covers my LGA fully

##OSM waterways extracted, via QuickOSM
Query: Rivers =* within Lokoja lga extent
Extracted date: 9/13/2026
1,247 features, lines
Many have no surface tag, so paved and unpaved cannot be separated  
The study area is Lokoja, Kogi State, Nigeria.

The study-area boundary was derived from GRID3 ward data using
Lokoja A, Lokoja B, Lokoja C, Lokoja D and Lokoja E wards.

The selected wards were combined to create a single Lokoja study-area
boundary.

## CRS and Preparation

Source datasets were checked for their coordinate reference systems
before processing.

The Lokoja study area falls within UTM Zone 32N.

Working projected vector data were reprojected to:

EPSG:32632 - WGS 84 / UTM Zone 32N

## Processing

The Lokoja A-E study-area boundary was used to clip relevant datasets.

Processed datasets include clipped spatial data for the Lokoja study
area.

Area calculations were performed using projected UTM data and
converted to square kilometres.

## Data Organization

Original source datasets are stored in:

data/raw/

Processed working datasets are stored in:

data/processed/

The original files in data/raw/ were not modified.

## Validation

The CRS of the working layers was checked before clipping.

The calculated study-area area was checked as a sanity check to
identify possible CRS or geometry errors.


