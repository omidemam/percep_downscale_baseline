# percep_downscale_baseline

This repository provides eight baseline methods for **temporal downscaling of precipitation**, using NOAA's regional temporal rainfall patterns. The goal is to convert daily rainfall totals into high-resolution (hourly) time series for hydrologic applications.

## Overview

We use daily accumulated rainfall fields derived from the AORC dataset and apply NOAA Atlas 14 temporal distributions to disaggregate them into hourly rainfall fields. Specifically:

- **Daily rainfall fields** are generated from AORC data.
- **Eight NOAA temporal patterns** (Region 2, Atlas 14) are used to disaggregate daily rainfall.
- **Hourly rainfall plots** are produced for hours 2, 5, 10, 15, and 20 as examples.

This approach can support flood modeling, stormwater design, and climate resilience analysis by incorporating realistic sub-daily rainfall variation from NOAA temporal patterns.

> **Note:** The Region 2 temporal distributions can help better reflect the intra-day variability seen in Atlas 14 rainfall events, particularly in the Northeastern U.S.

## Repository Contents

```plaintext
📁 Figure/                  # Visualizations of downscaled rainfall at select hours
📁 rainfall patterns/       # Contains the eight NOAA temporal distribution patterns
📄 Temporal_downscaling_baselines.ipynb   # Main notebook for downscaling and visualization
📄 LICENSE                  # Licensing information
📄 README.md                # This file

## Getting Started

To clone this repository and get started:

```bash
git clone https://github.com/omidemam/percep_downscale_baseline.git
