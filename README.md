# LSVC-Geo

**A Lightweight Settlement Vector Control Framework for Geolocating Remote Sensing Images without Spatial Reference**

Official repository for **LSVC-Geo**, a lightweight remote-sensing geolocation framework based on georeferenced settlement vector control.

> **Release Status**
>
> The associated manuscript is currently under review.
>
> This repository currently provides the project overview, method description, experimental configuration, and example materials. The full source code and reproducibility package will be released upon publication of the associated paper.

## Overview

Geolocating remote sensing images with missing or unreliable spatial reference is important for historical data recovery, automated image archiving, and the integration of heterogeneous geospatial data.

LSVC-Geo replaces complete reference imagery with georeferenced settlement vectors and reformulates remote-sensing image geolocation as a spatial-structure consistency problem.

The framework integrates:

* Rotation-consistent structural representation
* Transformation-parameter voting
* Hierarchical structural verification
* Local transformation refinement
* Confidence estimation

## Framework

The overall LSVC-Geo framework consists of three major stages:

1. **Rotation-consistent structural representation**
2. **Global transformation candidate generation**
3. **Hierarchical structural verification and refinement**


## Repository Structure

```text
LSVC-Geo/
├── README.md
├── requirements.txt
├── .gitignore
├── run.py
├── configs/
│   └── default.yaml
└── example/
    ├── query_mask.png
    └── expected_result_top30.jpg
```

The implementation modules will be added with the full source-code release.

## Code Availability

The full LSVC-Geo implementation is currently being prepared for public release.

**The complete source code and reproducibility package will be released upon publication of the associated paper.**

This staged release is intended to keep the public repository synchronized with the archival version of the associated publication.

## Citation

The associated manuscript is currently under review.

Complete citation information, including the DOI and BibTeX entry, will be added after publication.


