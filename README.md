
# Assessing the Relationship Between Forest Fires and PM2.5 Levels in India

## Project Overview
This repository contains the data, code, and documentation for the research project titled "Assessing the Relationship Between Forest Fires and PM2.5 Levels in India", conducted as a term paper for EES 502 at the Indian Institute of Science Education and Research, Bhopal. The study investigates the spatial and temporal relationships between forest fires and PM2.5 concentrations across three regions in India: Central India (Madhya Pradesh and Chhattisgarh), Northeast India (Arunachal Pradesh, Assam, Manipur, Meghalaya, Mizoram, Nagaland, Tripura), and the Northern Himalayan region (Uttarakhand and Himachal Pradesh). The analysis leverages high-resolution satellite datasets and statistical methods to quantify fire-PM2.5 dynamics, identify regional variations, and inform air quality and fire management strategies under frameworks like the National Clean Air Programme (NCAP).

## Data Sources

*   **FIRMS Active Fire Data (MODIS, 2003-2023):** Sourced from NASA's Fire Information for Resource Management System, providing daily fire detections at 1-km resolution.
*   **LGHAP v2 PM2.5 Data (2017-2021):** High-resolution (1-km) daily PM2.5 concentrations from the Local-Global Health Air Pollution dataset.
*   **LULC Data (2005):** Land Use and Land Cover map derived from Landsat and IRS satellite imagery, classified per the IGBP scheme.

## Methodology

The study employs:

*   **Data Preprocessing:** Aggregates fire and PM2.5 data to 10-km resolution for compatibility.
*   **Time-Series Analysis:** Examines monthly and yearly fire counts to identify seasonal and long-term trends.
*   **Correlation Analysis:** Computes region-wide and grid-scale correlations between fire counts and PM2.5 levels.
*   **Granger Causality Test:** Assesses whether fire counts predict PM2.5 concentrations at lags 1–7.
*   **Spatial Analysis:** Uses contour maps to visualize grid-scale correlations alongside LULC data.

## Key Findings

*   **Northeast India:** Strong fire-PM2.5 correlations (`r` > 0.5) and significant Granger causality at lags 1 and 5, driven by shifting cultivation.
*   **Central India:** Negligible region-wide correlations (`r` = -0.02), but a PM2.5 hotspot in southern Chhattisgarh’s deciduous forests.
*   **Northern Himalayan Region:** No clear fire-PM2.5 link due to minimal fire activity and rapid pollutant dispersal.

## Policy Implications

*   Region-specific fire management and air quality strategies are needed, aligned with the National Clean Air Programme (NCAP) and the National Action Plan on Forest Fires (NAPFF).

## Limitations

*   PM2.5 data is limited to 2017–2021, restricting long-term trend analysis.
*   The 10-km resolution may obscure fine-scale variations.
*   The Granger causality test assumes linearity, potentially missing complex dynamics.
*   The focus on three regions limits generalizability to other areas like the Western Ghats.

## Future Directions

*   Integrate meteorological data (e.g., wind, humidity) to assess PM2.5 dispersal.
*   Use source apportionment techniques to distinguish fire vs. non-fire PM2.5 sources.
*   Apply atmospheric transport models (e.g., HYSPLIT) to track aerosol pathways.
*   Develop predictive machine learning models for PM2.5 episodes in Northeast India.

## References

Refer to `Project_report.pdf` for the full list of references cited in the study.

## Contact

For questions, contact Saurabh Toraskar at [saurabhtoraskar31@gmail.com](mailto:saurabhtoraskar31@gmail.com).
Use code with caution.



