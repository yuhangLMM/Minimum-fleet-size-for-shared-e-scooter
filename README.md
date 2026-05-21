# Minimum-fleet-size-for-shared-e-scooter
This repository provides a simplified reproducibility notebook for the minimum fleet sizing procedure used in the Indianapolis e-scooter case study.

The notebook includes:

1. preprocessing the public Purdue Indianapolis e-scooter trip data;
2. generating an OD trip table by matching trip origins and destinations to census tracts;
3. calculating the minimum fleet size using a trip-chain algorithm.

## Data

The original trip data are publicly available from Purdue University:

- Dataset: Micromobility data set for Indianapolis
- DOI: 10.4231/3FT5-MJ18
- Required file: `purr_scooter_data.csv`

Please download the data yourself and place it under:

```text
data/purr_scooter_data.csv
