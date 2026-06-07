# Awesome Meteorology 🌪️

A curated list of amazingly awesome atmospheric science and meteorology resources, open datasets, weather APIs, software, and forecasting tools.

Whether you are a seasoned atmospheric scientist, a student learning synoptic meteorology, or a weather enthusiast building your first Python script, this is your one-stop shop.

---

## Table of Contents
- [Education & Coursework](#education--coursework)
- [Forecasting & Prediction Platforms](#forecasting--prediction-platforms)
- [Software & Python Libraries](#software--python-libraries)
- [AI & Machine Learning](#ai--machine-learning)
- [Open Datasets & APIs](#open-datasets--apis)
- [Career & Community](#career--community)
- [Contributing](#contributing)

---

## Education & Coursework

### Open Courseware (University Level)
* [COMET MetEd](https://www.meted.ucar.edu/) - Hundreds of free, highly-detailed training modules on meteorology, forecasting, and atmospheric science. (Requires free account).
* [MIT OpenCourseWare (EAPS)](https://ocw.mit.edu/search/?d=Earth%2C%20Atmospheric%2C%20and%20Planetary%20Sciences) - Free lecture notes, exams, and videos from MIT's atmospheric science classes (e.g., *Tropical Meteorology*, *Atmosphere, Ocean and Climate Dynamics*).
* [Penn State E-Education](https://www.e-education.psu.edu/) - Fantastic open courseware covering atmospheric thermodynamics, synoptic meteorology, and more.
* [HarvardX: Backyard Meteorology](https://www.edx.org/learn/natural-sciences/harvard-university-backyard-meteorology-the-science-of-weather) - A free introductory edX course focusing on observing physical processes and forecasting without instruments.

### Beginner & Hobbyist Resources
* [NWS JetStream](https://www.weather.gov/jetstream/) - The National Weather Service's online school for weather. A fantastic, comprehensive primer on weather basics.
* [NOAA SciJinks](https://scijinks.gov/) - Aimed at a younger or truly beginner audience, explaining weather and Earth science concepts with engaging interactive tools.
* [The GLOBE Program](https://www.globe.gov/) - An international science and education program that lets the public actively participate in atmospheric data collection.
* [MIT Aviation Meteorology Lecture](https://www.youtube.com/watch?v=W3a4F4pT7Zc) - A phenomenal one-hour lecture from MIT's Private Pilot Ground School covering weather theory, hazards, and turbulence.

## Forecasting & Prediction Platforms

### Numerical Weather Prediction (NWP) Model Viewers
* [Pivotal Weather](https://www.pivotalweather.com/) - A go-to platform for operational weather models (GFS, ECMWF, HRRR), soundings, and winter weather parameters.
* [Tropical Tidbits](https://www.tropicaltidbits.com/) - Levi Cowan's fantastic site, specializing in tropical cyclone tracking, hurricane aircraft recon data, and clean global model visualizations.
* [Meteologix (Weather.us)](https://weather.us/model-charts) - Features high-resolution European models (Swiss HD, ICON-D2) and massive archives of global weather parameters.
* [WxCharts](https://www.wxcharts.com/) - A very clean, European-developed interface for viewing major global models including the ECMWF, GFS, UKMO, and ICON.

### Interactive Global Visualization Maps
* [Windy.com](https://www.windy.com/) - An incredibly smooth, interactive global map for visualizing wind, temperature, waves, and CAPE using ECMWF, GFS, and ICON data.
* [Ventusky](https://www.ventusky.com/) - A highly visual, interactive web-based map developed in the Czech Republic, excellent for visualizing complex meteorological data and wind streams.
* [Earth Nullschool](https://earth.nullschool.net/) - A mesmerizing visualization of global weather conditions forecast by supercomputers, updated every three hours.

### Radar, Satellite & Nowcasting
* [College of DuPage (COD) NEXLAB](https://weather.cod.edu/) - Unarguably one of the best free interfaces for high-resolution GOES satellite imagery and local NEXRAD radar data.
* [NWS Radar](https://radar.weather.gov/) - The official, newly updated National Weather Service GIS-based radar interface for the United States.
* [RadarOmega](https://www.radaromega.com/) - A highly detailed, enthusiast-tier radar and tracking platform (Note: Desktop/Mobile app heavily focused on storm chasing).

### Operational Government Agencies
* [Storm Prediction Center (SPC)](https://www.spc.noaa.gov/) - The official US agency for severe thunderstorm/tornado outlooks, mesoscale discussions, and fire weather.
* [National Hurricane Center (NHC)](https://www.nhc.noaa.gov/) - The official source for tropical cyclone tracking, cones of uncertainty, and marine forecasts in the Atlantic and East Pacific.
* [Weather Prediction Center (WPC)](https://www.wpc.ncep.noaa.gov/) - Essential for Quantitative Precipitation Forecasts (QPF), winter weather probabilities, and national surface analysis charts.
* [Aviation Weather Center (AWC)](https://aviationweather.gov/) - The ultimate source for METARs, TAFs, PIREPs, icing forecasts, and aviation hazards.

## Software & Python Libraries

### General Meteorology & Analysis
* [MetPy](https://unidata.github.io/MetPy/) - The absolute gold standard for meteorology in Python. Packed with tools for reading, visualizing, and performing calculations (skew-Ts, kinematics, frontogenesis) with weather data.
* [Siphon](https://unidata.github.io/siphon/) - A collection of Python utilities for downloading data from remote data services, specifically designed to pull from THREDDS catalogs.
* [Tropycal](https://tropycal.github.io/tropycal/) - A fantastic Python package designed specifically for retrieving and analyzing tropical cyclone data (both historical and real-time).
* [wrf-python](https://wrf-python.readthedocs.io/) - A collection of diagnostic and interpolation routines specifically designed for extracting and working with output from the Weather Research and Forecasting (WRF-ARW) model.

### Data Wrangling & Formats
* [xarray](https://xarray.pydata.org/) - An essential library for working with multi-dimensional arrays, heavily used in climate science for manipulating NetCDF files.
* [cfgrib / pygrib](https://github.com/ecmwf/cfgrib) - Crucial libraries for reading and writing GRIB files (the standard format for operational weather models like the GFS and ECMWF).
* [CliMetLab](https://climetlab.readthedocs.io/) - An ECMWF package designed to greatly reduce boilerplate code by providing high-level unified access to meteorological and climate datasets.

### Radar, Satellite, & Remote Sensing
* [Py-ART](https://arm-doe.github.io/pyart/) - The Python ARM Radar Toolkit. The definitive library for reading, manipulating, and visualizing weather radar data (Level 2, Level 3, CF/Radial).
* [Satpy](https://satpy.readthedocs.io/) - A powerful library for reading, manipulating, and writing data from remote-sensing, earth-observing satellite instruments (like GOES and Meteosat).
* [wradlib](https://wradlib.org/) - An open-source library specifically focused on weather radar data processing, heavily used in Europe.

### Mapping & Visualization
* [Cartopy](https://scitools.org.uk/cartopy/) - A Python package designed for geospatial data processing in order to produce high-quality maps and handle complex map projections.
* [GeoCAT](https://geocat.ucar.edu/) - The Geoscience Community Analysis Toolkit by NCAR, essentially serving as the Python replacement for the legacy NCAR Command Language (NCL) for plotting and visualization.

## AI & Machine Learning

### Global Weather Models (Large Weather Models)
* [Google DeepMind GraphCast](https://github.com/google-deepmind/graphcast) - A state-of-the-art machine learning model that generates 10-day medium-range forecasts at 0.25° resolution using Graph Neural Networks.
* [Huawei Pangu-Weather](https://github.com/198808xc/Pangu-Weather) - A highly accurate 3D high-resolution AI weather model utilizing Earth-specific transformers.
* [NVIDIA FourCastNet](https://github.com/NVlabs/FourCastNet) - A global data-driven high-resolution weather model utilizing Adaptive Fourier Neural Operators (AFNO) to predict atmospheric variables.
* [Google NeuralGCM](https://github.com/neuralgcm/neuralgcm) - A breakthrough hybrid model combining traditional physics-based fluid dynamics with machine learning for both short-term weather and long-term climate simulation.

### Model Runners & Inference Tools
* [ECMWF ai-models](https://github.com/ecmwf-lab/ai-models) - An incredibly useful, official ECMWF Python tool specifically designed to run inference on various AI weather models (GraphCast, Pangu, FourCastNet) and seamlessly output the data in standard GRIB formats.
* [NVIDIA Earth2Studio](https://github.com/NVIDIA/earth2studio) - An open-source, Python-based deep-learning framework associated with NVIDIA's Earth-2 digital twin platform, built for running and exploring high-resolution climate and weather simulations.

### Specialized AI & Downscaling
* [DeepMind Nowcasting](https://github.com/deepmind/deepmind-research/tree/master/nowcasting) - Code focused on generative modeling for highly accurate, short-term precipitation nowcasting using deep learning and radar data.
* [ClimaX](https://github.com/microsoft/ClimaX) - Microsoft's foundational model for weather and climate, designed to be pre-trained on heterogeneous datasets and easily fine-tuned for various downstream forecasting tasks.

## Open Datasets & APIs

### Free Weather & Forecasting APIs
* [Open-Meteo](https://open-meteo.com/) - A phenomenal, highly reliable open-source weather API offering free access to historical, forecast, and marine data without needing API keys.
* [National Weather Service (NWS) API](https://www.weather.gov/documentation/services-web-api) - The official REST API from the US Government for pulling point forecasts, active alerts, and grid-based observation data. Completely free.
* [OpenWeatherMap API](https://openweathermap.org/api) - Provides global weather data, forecasts, and historical archives. They offer a very generous "One Call API" free tier for developers and student projects.
* [Tomorrow.io Weather API](https://www.tomorrow.io/weather-api/) - A robust commercial API with a solid free tier, providing hyper-local forecasting, real-time observation, and specialized layers like air quality.

### Cloud-Hosted & Massive Datasets
* [NOAA Open Data Dissemination (NODD)](https://www.noaa.gov/information-technology/open-data-dissemination) - The holy grail for bulk data. Access massive NOAA datasets (like NEXRAD radar Level 2/3, GOES satellite imagery, and HRRR/GFS models) directly hosted on AWS, Google Cloud, and Azure. 
* [Copernicus Climate Data Store (CDS)](https://cds.climate.copernicus.eu/) - The ultimate portal for European climate data, offering petabytes of open data including the highly utilized ERA5 global climate reanalysis dataset. 
* [ECMWF Open Data](https://www.ecmwf.int/en/forecasts/datasets/open-data) - Free and open access to ECMWF's medium-range, extended-range, and extreme forecast model data.
* [Registry of Open Data on AWS (Climate & Weather)](https://registry.opendata.aws/collab/noaa/) - A direct catalog of all atmospheric, oceanic, and climate datasets freely hosted on Amazon Web Services.

### Aviation & Specialized Data
* [Aviation Weather Center (AWC) Data API](https://aviationweather.gov/data/api/) - The official API for fetching raw METARs, TAFs, PIREPs, aircraft reports, and SIGMETs for aviation meteorology.
* [IEM (Iowa Environmental Mesonet) API](https://mesonet.agron.iastate.edu/api/) - A massive, community-favorite repository and API for pulling historical ASOS/AWOS station data, NEXRAD composites, and severe weather warning polygons.

## Career & Community
* [American Meteorological Society (AMS)](https://www.ametsoc.org/) - The premier scientific and professional organization promoting and disseminating information about the atmospheric, oceanic, and hydrologic sciences.
* [r/meteorology](https://www.reddit.com/r/meteorology/) - A Reddit community for discussing atmospheric sciences, forecasting, and related academic topics.

---

## Contributing

Contributions are very welcome! Please read our [Contribution Guidelines](CONTRIBUTING.md) before submitting a Pull Request. 

## License

This project is licensed under the [MIT License](LICENSE).
