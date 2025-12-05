---
layout: default 
title: "Data Driven Modeling in Earth and Environmental Science"
permalink: "/teaching/T001/syllabus"
---

# Data Driven Modeling in Earth and Environmental Science 
<br/>

## Course description
This course introduces data driven techniques used to analyze Earth and environmental observations and model outputs. Students learn fundamental data handling skills, exploratory analysis, and modern machine learning approaches tailored to environmental systems. Emphasis is placed on understanding the meaning of patterns, variability, and uncertainty in the Earth system rather than on purely computational or algorithmic knowledge. Through hands on coding activities and real world examples from the ocean, atmosphere, hydrosphere, and biosphere, students learn how data driven methods can reveal processes, improve predictions, and support scientific discovery in the environmental sciences.
<br/>

## Learning goals
- **Environmental Data and Preprocessing:** <br/>
Identify major Earth system datasets and apply essential preprocessing to prepare data for analysis

- **Exploratory Data Analysis:** <br/>
Characterize variability in environmental data across time and space using standard analysis techniques

- **Data Driven Modeling and Evaluation:** <br/>
Build and assess statistical models that explain and predict environmental processes

- **Machine Learning for Earth System Applications:** <br/>
Apply machine learning methods to Earth system data and communicate results with reproducible workflows

<br/>

## Course Topics and Outline
### <font color="#A52A3A">Part I: Data of the earth system</font>
### Lecture 1:	Observational Data in Earth Science
Students learn how coastal, oceanic, atmospheric, and terrestrial environments are measured. Topics include satellites for sea surface height and vegetation, buoys and Argo profiles for ocean water properties, eddy covariance towers for land carbon fluxes, and river gauging networks. Focus on the strengths and limitations of each observing system for scientific inference.

**Homework:** <br/>
Collect a set of data in earth and environment sciences and describe this set of data

### Lecture 2:	Model and Reanalysis Data
Introduction to general earth system models and the role of data assimilation in reanalysis. Students learn differences between observations and model results, common biases, and appropriate usage in climate and Earth system studies including CMIP model projections and atmospheric reanalyses. 

***References:*** <br/>
Eyring et al., 2016. Overview of the Coupled Model Intercomparison Project Phase 6 (CMIP6) experimental design and organization. Geoscientific Model Development, 9(5), pp.1937-1958. [[link]](https://gmd.copernicus.org/articles/9/1937/2016/gmd-9-1937-2016.pdf)

### Lecture 3:	Earth Data Formats and Handling
Hands on training with NetCDF and multidimensional data tools like xarray. Students work with Earth data such as MODIS chlorophyll or NOAA sea surface temperature, learning slicing, masking, and metadata interpretation. 

**Homework:** <br/>
Download, process, and plot a set of NetCDF data in python or MATLAB.

### Lecture 4:	Data Quality Control and Preprocessing
How to screen and correct environmental datasets. Includes checking instrument drift, removing outliers in ocean sensors, temporal filtering in climate indices, detrending temperature records, and computing anomalies relative to climatology.

***References:*** <br/>
Kennedy, J.J., 2014. A review of uncertainty in in situ measurements and data sets of sea surface temperature. Reviews of Geophysics, 52(1), pp.1-32. [[link]](https://agupubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/2013RG000434)

<br/>

### <font color="#A52A3A">Part II: Basics of data-driven analysis methods</font>
### Lecture 5:	Exploratory Analysis of Environmental Data
Focus on variability patterns in environmental systems. Topics include autocorrelation in climate indices, spatial covariance of sea surface temperature, and spectra of sea level and wind time series. Students analyze datasets using standard Earth science workflows.

***References:*** <br/>
Deser, C., Alexander, M.A., Xie, S.P. and Phillips, A.S., 2010. Sea surface temperature variability: Patterns and mechanisms. Annual review of marine science, 2, pp.115-143. [[link]](https://staff.cgd.ucar.edu/asphilli/docs/deser.sstvariability.annrevmarsci10.pdf)

### Lecture 6:	Regression Tools for Earth System Applications
How linear and nonlinear regression support prediction and attribution studies, for example linking rainfall to large scale climate drivers or relating primary productivity to nutrients. Students interpret physical meaning of coefficients and uncertainties.

***References:*** <br/>
Da, F., Stock, C.A., Dunne, J.P., Liu, X., Luo, J.Y., Lee, M. and Shevliakova, E., 2025. A global perspective on river alkalinity: Drivers and implications for coastal ocean carbonate chemistry. Global Biogeochemical Cycles, 39(11), p.e2025GB008528. [[link]](https://agupubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1029/2025GB008528)

### Lecture 7:	Dimensionality Reduction in the Geophysical Context
EOF and PCA methods applied to climate phenomena such as ENSO or modes of sea level variability. Students learn interpretation of spatial patterns and caution against over interpretation when sampling is limited.

***References:*** <br/>
Wilks, D.S., 2011. Principal component (EOF) analysis. In International geophysics (Vol. 100, pp. 519-562). Academic press. [[link]](https://1drv.ms/b/c/11cf3b5a8c24a791/IQANxSs91SxnQqajAXl-hRlaASWNTwNOnEQ9p0LFRSUnUcM?e=qItZ7N) <br/>
Champenois, B. and Sapsis, T., 2024. Machine learning framework for the real-time reconstruction of regional 4D ocean temperature fields from historical reanalysis data and real-time satellite and buoy surface measurements. Physica D: Nonlinear Phenomena, 459, p.134026. [[link]](https://1drv.ms/b/c/11cf3b5a8c24a791/IQB-VTxfsze4RoaE0tSl1LtoAZhEwNhDIYkDx0eTD80DQTc?e=AiBljH)

### Lecture 8:	Validation, Cross Validation, and Uncertainty in Environmental Prediction
Model validation for seasonal forecasts, hydrologic predictions, and ecological indicators. Introduces skill metrics used in environmental assessments including reliability diagrams and RMSE.

***References:*** <br/>
Chai, T. and Draxler, R.R., 2014. Root mean square error (RMSE) or mean absolute error (MAE)?–Arguments against avoiding RMSE in the literature. Geoscientific model development, 7(3), pp.1247-1250. [[link]](https://gmd.copernicus.org/articles/7/1247/2014/gmd-7-1247-2014.pdf)

<br/>

### <font color="#A52A3A">Part III: Common machine-learning methods</font>
### Lecture 9:	Decision Trees and Random Forests in Earth Science
Applications examples including water quality classification, flood risk mapping, land cover recognition, and drought monitoring. Covers interpretability and feature importance for physical system insights.

***References:*** <br/>
Mobley, W., Sebastian, A., Blessing, R., Highfield, W.E., Stearns, L. and Brody, S.D., 2021. Quantification of continuous flood hazard using random forest classification and flood insurance claims at large spatial scales: a pilot study in southeast Texas. Natural Hazards and Earth System Sciences, 21(2), pp.807-822. [[link]](https://nhess.copernicus.org/articles/21/807/2021/nhess-21-807-2021.pdf)

### Lecture 10:	Neural Networks for Environmental Prediction
Learn how neural networks handle nonlinear relationships such as predicting hurricane intensity, climate pattern recognition, or air quality forecasts. Introduces convolutional networks for gridded climate fields.

***References:*** <br/>
Gibson, P.B., Chapman, W.E., Altinok, A., Delle Monache, L., DeFlorio, M.J. and Waliser, D.E., 2021. Training machine learning models on climate model output yields skillful interpretable seasonal precipitation forecasts. Communications Earth & Environment, 2(1), p.159. [[link]](https://www.nature.com/articles/s43247-021-00225-4.pdf)

### Lecture 11:	Clustering and Classification for Environmental Phenomena
Unsupervised learning used to discover natural groups including water masses, vegetation biomes, or marine heatwave regimes. Students learn how techniques reveal patterns that suggest underlying processes.

***References:*** <br/>
Sonnewald, M., Dutkiewicz, S., Hill, C. and Forget, G., 2020. Elucidating ecological complexity: Unsupervised learning determines global marine eco-provinces. Science advances, 6(22), p.eaay4740. [[link]](https://www.science.org/doi/pdf/10.1126/sciadv.aay4740)

### Lecture 12:	Physics Guided and Hybrid Machine Learning
Focuses on integrating scientific principles and using AI emulators for fast approximations of Earth system models. Examples include streamflow prediction using hybrid constraints and coastal flood models augmented by data.

***References:*** <br/>
Liu, L., Zhou, W., Guan, K., Peng, B., Xu, S., Tang, J., Zhu, Q., Till, J., Jia, X., Jiang, C. and Wang, S., 2024. Knowledge-guided machine learning can improve carbon cycle quantification in agroecosystems. Nature communications, 15(1), p.357. [[link]](https://www.nature.com/articles/s41467-023-43860-5.pdf)

<br/>

## Resources

#### Books
- [An Introduction to Earth and Environmental Data Science](https://earth-env-data-science.github.io/intro.html)
- [Statistical Methods in the Atmospheric Sciences](https://1drv.ms/b/c/11cf3b5a8c24a791/IQCXBBayKqpmTKSQo9eHFRU8AabC-sdsew1bG4cdWw7JNAY?e=jB10Hj)
- [Data Analysis Methods in Physical Oceanography](https://www.sciencedirect.com/book/monograph/9780123877826/data-analysis-methods-in-physical-oceanography)
- [Deep Learning for the Earth Sciences: A Comprehensive Approach to Remote Sensing, Climate Science, and Geosciences](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119646181?utm_source=chatgpt.com)
- [Machine Learning for Earth Sciences](https://link.springer.com/book/10.1007/978-3-031-35114-3?utm_source=chatgpt.com)
- [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- [Deep Learning](https://www.deeplearningbook.org)


#### Data sources
- [NOAA Tides and Currents](https://tidesandcurrents.noaa.gov/map/)
- [AMERIFLUX](https://ameriflux.lbl.gov/sites/site-search/)
- [Copernicus Marine Data](https://data.marine.copernicus.eu/products)
- [Chesapeake Bay Water Quality Monitoring](https://datahub.chesapeakebay.net/WaterQuality)
- [USGS National Water Dashboard](https://dashboard.waterdata.usgs.gov/app/nwd/en/)
- [NOAA World Ocean Database](https://www.ncei.noaa.gov/products/world-ocean-database)

