# Sentinel-2 Crop Mapping Module
There is a pressing need for innovative approaches to monitor smallholder farms, particularly in developing nations where these farms are the primary focus of policy goals yet often without the resources necessary for forecasting or recording production trends.

This module uses georeferenced satellite imagery to meet this need. The imagery is collected by ESA's [Sentinel-2 mission](https://sentinel.esa.int/web/sentinel/missions) whose onboard MultiSpectral Instrument (MSI) registers light reflectance information from earth within 13 spectral bands ranging from Visible and Near-Infrared (VNIR) to Shortwave Infrared (SWIR) wavelengths. It runs the orthorectified Bottom-of-Atmosphere reflectance through a preprocessing pipeline to obtain spectral indices of interest and models the time series of imagery using harmonic regression. Finally, we train an ensemble to identify crop type over a region of interest, which classical downstream applications can immediately use e.g for yield estimation.

Completed under supervision of Dr. Subhashish Banerjee and Dr. Raghavendra Singh.
