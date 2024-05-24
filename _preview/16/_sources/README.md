<img src="notebooks/images/saillogo.png" alt="thumbnail" width="300"/>

# SAIL Cookbook: Aerosol influence on ground snow properties during SAIL

## Group Members
Yan Xie, Zhenli Lai (Joy), Maiqi Zhang, Jessica Gasparik, Hayden Webb, Ryan Poland, Adrian Cortes

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11282356.svg)](https://doi.org/10.5281/zenodo.11282356)

The Colorado River provides water resources to the local community and ecosystems, 15 million jobs, and hydroelectric energy. However, the Colorado River has been under extreme stress with decreases in stream and river discharge in the basin. Many studies investigate reasons behind the changing in river conditions. On September 1, 2021 an ARM field campaign known as Surface Atmosphere Integrated Field Laboratory (SAIL) was launched to advance knowledge of atmospheric processes at high altitude terrain. The field campaign extended through June 15, 2023 with the ARM Mobile Facility (AMF2) deployed to Gunnison, CO. Measurements in precipitation, atmospheric thermodynamic state, aerosols and many more were collected over the period of study. 

Our analysis utilizes SAIL data to observe changes in snow properties due to high aerosol loading events. The analysis considers a high black carbon event on January 25th, 2022 caused by wildfire smoke advecting over the Colorado site from California. The second event considers a known high dust loading event on April 3rd, 2023. These events are validated using HYSPLIT simulations. We analyze the aerosol present using data from the ARM2 including SMPS, SP2, OPC, Lidar. This project evaluates changes in albedo, longwave radiation, and snowpack due to high aerosol loading events. The events are compared to WRF simulations for the SAIL campaign, which do not include aerosol. This serves to validate our findings regarding aerosol influence on the surface snow properties. This work is motivated by understanding the aerosol influence on the local hydrologic cycle. 

## Science Question(s)
- Compare snowpack and surface radiative properties for two aerosol events (high dust and high black carbon (BC)) and one control case.
- Dates under consideration: January 2nd 2022 (control), January 25th 2022 (black carbon event), April 3rd 2023 (dust event). We will consider 5 days after each event.
- How do these peaks correlate with changes surface albedo, radiative fluxes & snowpack?
* Quantify errors in WRF simulations which do not consider aerosol. Observe differences in surface albedo, radiative fluxes and snowpack depth.
* Motivation: Observe the impact of high aerosol loading on the local hydrologic cycle.

## Project Scope (what does success look like)?
* **Aerosol (observations):** plot total number concentration, plot black carbon and dust mixing ratios (or proxy variable)
* **Surface snow impact (observations):** Plot changes in snowpack, surface albedo, and radiative fluxes surrounding high aerosol events
* **Model comparison:** WRF simulations at the same dates, quantify errors in snowpack, surface albedo, and radiative fluxes. Errors = observed - modeled.

## Hypothesis (or Hypotheses)
- Decreases in local surface albedo will correlate with high aerosol loading events. 
- Increased surface heating results in snowpack depth decrease following high aerosol loading events.
- WRF does not implement aerosols in simulations; therefore, could mis predict the snow radiation fluxes following aerosol events.

## Datasets
* **SP2 measurement** - black carbon
* **Lidar** - dust
* **SMPS** - total number concentration&size distribution
* **HYSPLIT**-back trajectories
* **SEBS measurement** - surface shortwave radiation fluxes
* **MET measurement** - surface temperature; precipitation
* **WRF simulation** - surface radiation fluxes; snow depth (?); surface temperature
* **AOP PSAP** - aerosol optical properties (AAE, AE, SSA, Beta Abs, Beta Sca)
* **Weather camera** - snow cover status

