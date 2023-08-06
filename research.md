---
layout: cv
title: Research
---

- toc
{: toc }

## Ongoing research

### Interpret continental-scale OH trends in climate models

![placeholder](/assets/oh-trend-climate.png "OH trends in CESM2 climate model")

The hydroxyl radical (OH) lies at the nexus of climate and air quality as the primary oxidant for both reactive greenhouse gases and many hazardous air pollutants. The lifetime of methane, a major anthropogenic greenhouse gas causing about one-half of the warming of carbon dioxide since pre-industrial times, is largely set by the global integral of OH concentrations, which vary strongly in space and time.

To better understand the spatiotemporal dynamics of OH, we utilize an existing 13-member ensemble of the CESM2-WACCM6 chemistry-climate coupled model spanning the years 1950 to 2014. A substantial spatial variation of historical trends of tropospheric column OH between 2005 and 2014 is observed. We then use a machine learning (ML) technique, a fully connected neural network, to emulate the annual mean tropospheric column OH and apply this emulator to identify the dominant drivers contributing to the regional variation in the OH trends.

### Develop RACM2B-VCP mechanism for WRF-Chem


Volatile organic compound (VOC) reactions with hydroxyl radicals (OH) and nitrogen oxides (NOx) fuel the production of air pollutants like ozone and particulate matter (PM). The representation of VOC chemistry remains challenging in reduced chemical mechanisms due to its complexity in speciation and reactions. We aim to develop a chemical mechanism that is compatible with WRF-Chem that better represents VOC chemistry in urban areas such as Los Angeles. We show that this chemical mechanism, RACM2B-VCP, is based on the RACM2_Berkeley2 mechanism and includes more complex oxygenated VOC chemistry to address the impact of VCP and cooking emissions. 

We will evaluate how well this RACM2B-VCP mechanism simulates VOC chemistry, ozone, and PM2.5 in WRF-Chem by comparing against a series of observations, including airborne measurements from the RECAP-CA field campaign, mobile and in-situ measurements from the SUNVEX field campaign as well as AQS networks in summer 2021 over the LA Basin. 


## Past research

### Airborne NO<sub>x</sub> flux measurement (RECAP-CA)

Nitrogen oxides (NO<sub>x</sub>) are principle components of air pollution and serve as important ozone precursors. As the San Joaquin Valley (SJV) experiences some of the worst air quality in the United States, reducing NO<sub>x</sub> emissions is a pressing need, yet quantifying current emissions is complicated due to a mixture of mobile and agriculture sources. We performed airborne eddy covariance flux measurements during the Re-Evaluating the Chemistry of Air Pollutants in CAlifornia (RECAP-CA) field campaign in June 2021. Combining footprint calculations and land cover statistics, we disaggregate the observed fluxes into component fluxes characterized by three different land cover types. 

The calculated NO<sub>x</sub> emissions using flux observations are utilized to evaluate anthropogenic emission inventories and soil NO<sub>x</sub> emission schemes. We show that two anthropogenic inventories for mobile sources, EMFAC (EMssion FACtor) and FIVE (Fuel-based Inventory for Vehicle Emissions), yield strong agreement with emissions derived from measured fluxes over urban regions. Three soil NO<sub>x</sub> schemes, including MEGAN v3 (Model of Emissions of Gases and Aerosols from Nature), BEIS v3.14 (Biogenic Emission Inventory System) and BDISNP (Berkeley Dalhousie Iowa Soil NO Parameterization), show substantial underestimates over the study domain. Compared to the cultivated soil NO<sub>x</sub> emissions derived from measured fluxes, MEGAN and BEIS are lower by more than one order of magnitude and BDISNP is lower by a factor of 2.2. Despite the low bias, observed soil NO<sub>x</sub> emissions and BDISNP present a similar spatial pattern as well as temperature dependence. We conclude that soil NO<sub>x</sub> is a key feature of the NO<sub>x</sub> emissions in the SJV and that a biogeochemical process-based model of these emissions is needed to simulate emissions for modeling air quality in the region.

### Estimate urban OH trends using ML

The OH radical is the most influential tropospheric oxidant. OH in urban areas is of great significance as it controls the fate and lifetime of pollutants such as NOx and VOCs and it initiates reactions leading to the formation of secondary photochemical pollutants such as ozone and organic aerosol. In this study we utilize machine learning with satellite remote sensing observational inputs to predict surface OH in 49 North American cities from 2005 to 2014. We discuss the decadal changes of summertime OH and probe the shifts of the chemical regime. We conclude that the cities in this analysis are all either already in the NOx limited regime or at the transition point between a NO<sub>x</sub> suppressed regime to NOx limited regime. The result emphasizes that controlling NOx emissions will be especially effective in regulating the ozone pollution over North American cities.

Publication: [Zhu et al., 2022a](https://pubs.acs.org/doi/10.1021/acs.est.1c05636), [Zhu et al., 2022b](https://www.pnas.org/doi/10.1073/pnas.2117399119) 

### Lightning NO<sub>2</sub> simulation over the Contiguous US and its effects on satellite NO<sub>2</sub> retrievals

![placeholder](https://phys.org/news/2009-10-nasa-explore-lightning-nox-ious-impact.html "lightning")

Lightning is an important NOx source representing ~10% of the global source of odd N and a much larger percentage in the upper troposphere. The poor understanding of spatial and temporal patterns of lightning contributes to large uncertainty in understanding upper tropospheric chemistry. We implement a lightning parameterization using the product of convective available potential energy (CAPE) and convective precipitation rate (PR) into Weather Research and Forecasting-Chemistry (WRF-Chem) model for 5 North America. We show that the CAPE-PR parameterization with a regional scaling factor of 0.5 in the southeastern US yields an improved representation of lightning flashes in WRF when compared against flash density from the Earth Networks Total Lightning Network. Compared to the cloud top height (CTH) lightning parameterization used in WRF-Chem, simulated NO2 profiles using the CAPE-PR parameterization exhibit better agreement with aircraft observations in the middle and upper troposphere. While the lightning NOx production rate is 500 mol NO flash −1, using the a priori NO2 10 profile generated by the simulation with the CAPE-PR parameterization reduces the air mass factor for NO2 retrievals by 16% on average in the southeastern US on the late spring and early summer; yielding an overall 20% enhancement of the NO2 vertical column density compared to simulations using the CTH lightning parameterization.

Publication: [Zhu et al., 2019](https://acp.copernicus.org/articles/19/13067/2019/) 
