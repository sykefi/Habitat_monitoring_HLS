# Habitat_monitoring_HLS
Habitat monitoring example with Harmonized Landsat-Sentinel data.

This tutorial demonstrates how to apply NASA’s Harmonized Landsat-Sentinel2 (HSL) data for habitat monitoring in R. It demonstrates how to query, extract and analyse useful information at habitat level from the HLS data time series.

The tutorial is adapted from NASA’s tutorial(1) for Finnish use case by Pekka Hurskainen and Mikko Kervinen (@mtkervinen) from Finnish Environment Institute (Syke). This work was supported by Finnish Ecosystem Observatory (FEO) project, funded by Ministry of Environment. Many thanks also to Janne Mäyrä from Syke (@mayrajeo) for helping with Github essentials.

Most important modifications to the original tutorial include:
a) use of rstac library instead of httr, which allows for example easy fetching of all available images matching your query
b) handling of HSL data in different UTM zones (in Finland)
c) cloudmasking using fmask

See the demonstration in R-markdown through your web browser: https://sykefi.github.io/Habitat_monitoring_HLS/

(1) Original tutorial by Aaron Friesz are available here: https://github.com/nasa/HLS-Data-Resources/blob/main/r/HLS_Tutorial.Rmd
