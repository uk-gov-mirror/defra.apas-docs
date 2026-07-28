# Meteorological settings

You must select a meteorological site and year for your calculation job. Two types of meteorological data are available:
- **Numerical Weather Prediction (NWP)** - computer-modelled meterological data 
- **observational** - measured meteorological data from specific sites

For the observational data sites, there are three types of data depending on the available data:
- **Raw >90% Random** - raw measurements at meteorological sites with at least 90% usable data (any gaps are less than 3h long, and total gaps make up no more than 10%) with gap filling via data from the site itself
- **Interpolated >75% Random** - meteorological sites that had less than 90% of the data but more than 75% data and then gaps were filled through interpolation from nearby met sites 
- **Wind sectors >90% Random** - at meteorological sites that only measure wind data, other parameters were taken from the closest met site and combined with this wind data (to include more observational site options)

When running five years of met data, the calculator will determine the maximum value for each hexagon within those five years and present that as the scenario result.

[Go to previous page](4-calculation-jobs.md)
