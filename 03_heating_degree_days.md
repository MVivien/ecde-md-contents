<br />**Context**

The Heating Degree Days index is relevant to energy. This Index is part of the Mean temperature Hazard type of the Heat and Cold category of the classification.

The index measures heat deficit by cumulating daily degrees below a temperature threshold. It is a proxy for the energy needed to heat a building. There are several implementations of these indices that use different underlying data (e.g. daily mean vs. daily minimum and maximum temperature), threshold temperatures, and possible seasonal restrictions (e.g. only predefined heating season). The definition used here uses a combination of daily mean, maximum and minimum temperature.

A higher value means lower temperatures and thus more energy demand for heating.

<br />**Definition**

The cumulative sum of daily degrees below a daily mean temperature of 15,5°C (°C day-1) over a period. The formulation adopted here is based on daily mean, maximum and minimum temperature.

<br />**Data Sources**

The data was assembled on behalf of the Copernicus Climate Change Service (C3S) based on climate projections hosted on the C3S Climate Data Store (CDS). The Index is calculated from the ERA5 reanalysis and the ERA5 reanalysis and a set of nine bias-corrected multi-model simulations from the EURO-CORDEX experiment. These simulations have a spatial resolution of 0.25° x 0.25°, a 3-hourly output, and cover scenarios RCP4.5 and RCP8.5. More information about the dataset can be found in the corresponding [CDS documentation resources](https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-energy-derived-projections).

<br />**Supporting Information**

Further information about this application can be found in the [Product User Guide (PUG)](https://datastore.copernicus-climate.eu/documents/ecde/3-ecde-app-heating-degree-days-v1.0.pdf) of the application in the documentation resources of the CDS.
