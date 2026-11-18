# GeoB1515-1 | Marine Sediment Core Analysis

**X-ray diffraction mineralogy, sediment composition, and paleoceanographic reconstruction**

This repository documents an ongoing marine geoscience project investigating the mineralogical composition of sediment core GeoB1515-1 from the western equatorial Atlantic Ocean.

The project combines X-ray diffraction (XRD) measurements, Python-based data analysis, geospatial visualization, and oxygen isotope stratigraphy to examine changes in sediment composition and their potential paleoceanographic significance.

An interactive presentation of the mineralogical data is available on the [project website](https://sylvia-marinegeo.github.io/projects/geob1515/).

## Study Area

GeoB1515-1 was recovered from the western equatorial Atlantic near the Ceará Rise, offshore northeastern South America.

| Parameter | Value |
|---|---|
| Core | GeoB1515-1 |
| Latitude | 4.24° N |
| Longitude | 43.67° W |
| Water depth | 3,129 m |
| Core recovery | 6.58 m |
| XRD sample records | 127 |

The sediment sequence provides an opportunity to investigate variations in carbonate mineralogy and sediment composition in the tropical Atlantic.

## Research Objectives

- Characterize carbonate mineral assemblages using XRD measurements.
- Investigate mineralogical changes throughout the sediment sequence.
- Compare carbonate and major silicate abundances.
- Examine unusual mineral occurrences and assess identification uncertainty.
- Develop an age–depth model using oxygen isotope stratigraphy and published chronological constraints.
- Create interactive scientific visualizations for exploring the dataset.

## Methods and Tools

**Mineralogical analysis**

XRD measurements are used to investigate calcite, Mg-rich calcite, aragonite, ankerite/dolomite, and siderite/magnesite.

Particular attention is given to uncertainties associated with mineral identification, sample preparation, and semiquantitative XRD analysis.

**Python data analysis**

Python notebooks are used for data processing, statistical analysis, and visualization.

The workflow includes:

- Processing and organizing mineralogical measurements.
- Calculating mineral group abundances and carbonate-normalized fractions.
- Examining depth-dependent mineralogical variability.
- Comparing carbonate and silicate components.
- Developing interactive Plotly visualizations.

**Geospatial analysis**

QGIS is used to visualize the core location and its regional bathymetric setting.

**Chronological analysis — in progress**

An age–depth model is being developed using oxygen isotope measurements, published radiocarbon ages, and marine isotope reference records.

Chronological interpretations remain preliminary pending validation of the age model.

## Preliminary Observations

The mineralogical dataset reveals several notable features:

**Near-surface aragonite enrichment**

Aragonite is relatively abundant in the upper sediment sequence, with reported values reaching 17.28% at 3 cm depth.

**Deeper aragonite occurrence**

A second interval of elevated aragonite abundance occurs around 418–428 cm.

**Unusual carbonate phase**

A reported siderite/magnesite occurrence at 203 cm requires further examination of the original diffraction pattern to assess mineral identification.

**Bulk sediment composition**

Carbonate and major silicate abundances exhibit a strong negative correlation (*r* = −0.932). Because these measurements represent compositional percentages, this relationship is influenced by the constant-sum constraint and should not be interpreted directly as evidence of opposing sediment accumulation rates.

These observations are preliminary and are not yet assigned to specific paleoceanographic events.

## Repository Contents

The repository contains Jupyter notebooks for sediment core data processing, mineralogical visualization, and age–depth model development.

The notebooks document the analytical workflow and ongoing investigations. Some components remain under development.

## Data and Attribution

XRD measurements were provided through the University of Bremen under the supervision of Dr. Christoph Vogt.

Permission to redistribute the underlying XRD dataset is being clarified. The original measurements should not be redistributed without authorization.

Published isotope and chronological datasets are attributed to their respective authors.

## References

Rühlemann, C., Diekmann, B., Mulitza, S., & Frank, M. (1998). *Stable isotopes of sediment core GeoB1515-1*. PANGAEA. https://doi.org/10.1594/PANGAEA.54617

Vidal, L., et al. (1999). *Age determination of sediment core GeoB1515-1*. PANGAEA. https://doi.org/10.1594/PANGAEA.56995

Vogt, C., Lauterjung, J., & Fischer, R. X. (2002). Investigation of the clay fraction (less than 2 μm) of the Clay Minerals Society reference clays. *Clays and Clay Minerals, 50*(3), 388–400. https://doi.org/10.1346/000986002760833765

Vogt, C. (2009). Data report: semiquantitative determination of detrital input to ACEX sites based on bulk sample X-ray diffraction data. *Proceedings of the Integrated Ocean Drilling Program, 302*. https://doi.org/10.2204/iodp.proc.302.203.2009

---

**Project:** B.Sc. Marine Geosciences, University of Bremen

**Status:** Ongoing research project
