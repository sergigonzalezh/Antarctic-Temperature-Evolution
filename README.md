# Polar-Temperature-Maps-and-Stripes
[Polar amplification](https://en.wikipedia.org/wiki/Polar_amplification) is the phenomenon that causes faster warming in the poles than planetary average. Polar amplification is evident in the [Arctic](https://tc.copernicus.org/articles/3/11/2009/). In Antarctica, [widespread warming](https://journals.ametsoc.org/view/journals/clim/32/20/jcli-d-18-0565.1.xml) is modulated by the climate modes of variability, that causes regional differences and [short-term periods](https://www.cambridge.org/core/journals/antarctic-science/article/how-robust-are-the-temperature-trends-on-the-antarctic-peninsula/50EDA910D7FF017077DC710FD1FCEA35) of warming and cooling in different regions.

This is a series of scripts to create plots with maps and stripes of the near-surface air temperature in the poles with [Jupyter notebook](https://jupyter.org/) used to create visualizations for the [Year of Polar Prediction](https://www.polarprediction.net/).

Scripts download data from [ERA5](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5) and [SCAR Met-READER](https://legacy.bas.ac.uk/met/READER/data.html) to visualize the annual surface temperature evolution in the Arctic and Antarctica.

In this repository you can find the following scripts:
* **Plot_annual_anomaly_Arctic.ipynb:** creates an annual map with the Arctic surface air temperature anomaly and warming stripes of the region

<img src="https://github.com/sergigonzalezh/Polar-Temperature-Maps-and-Stripes/blob/main/Tanomaly_AllArt_1950.png" width="200" height="200"> <img src="https://github.com/sergigonzalezh/Polar-Temperature-Maps-and-Stripes/blob/main/Tanomaly_AllArt_2020.png" width="200" height="200">
<img src="https://github.com/sergigonzalezh/Polar-Temperature-Maps-and-Stripes/blob/main/StripePlot_Art.png">

* **Plot_annual_anomaly_Arctic.ipynb:** creates an annual map with the Antarctic surface air temperature anomaly (including observations) and warming stripes of the region

<img src="https://github.com/sergigonzalezh/Polar-Temperature-Maps-and-Stripes/blob/main/Tanomaly_AllAnt_1950.png" width="200" height="200"> <img src="https://github.com/sergigonzalezh/Polar-Temperature-Maps-and-Stripes/blob/main/Tanomaly_AllAnt_2020.png" width="200" height="200">
<img src="https://github.com/sergigonzalezh/Polar-Temperature-Maps-and-Stripes/blob/main/StripePlot_Ant.png">

* **Plot_AntarcticStations_stripes.ipynb** creates the warming stripes of any Antarctic station in the SCAR Met-READER database

<img src="https://github.com/sergigonzalezh/Polar-Temperature-Maps-and-Stripes/blob/main/StripePlot_Orcadas.png">

It was used to create the Social Media video in [Twitter](https://twitter.com/polarprediction/status/1399293122270609409), [Instagram](https://www.instagram.com/p/CPlAynlKvWx/) and [Tik Tok](https://www.tiktok.com/@polarprediction/video/6967314928424242437?lang=es&is_copy_url=0&is_from_webapp=v1&sender_device=pc&sender_web_id=6955074349489686022).


Look also [Thomas Rackow's](https://github.com/trackow) [Melting Stripes](https://github.com/trackow/warmingstripes#readme) to visualize the Arctic Sea Ice decrease and the Antarctic Sea Ice variability.
