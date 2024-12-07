# Annual working hours per worker - Data package

This data package contains the data that powers the chart ["Annual working hours per worker"](https://ourworldindata.org/grapher/annual-working-hours-per-worker?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on December 07, 2024.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Average annual working hours per worker


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Our World in Data based on Huberman & Minns (2007) and PWT 9.1 (2019) – processed by Our World in Data

#### Full citation
Our World in Data based on Huberman & Minns (2007) and PWT 9.1 (2019) – processed by Our World in Data. “Average annual working hours per worker” [dataset]. Our World in Data based on Huberman & Minns (2007) and PWT 9.1 (2019) [original data].
Source: Our World in Data based on Huberman & Minns (2007) and PWT 9.1 (2019) – processed by Our World In Data

### Additional information about this data
From 1870–1938 the data is from Huberman & Minns (2007). From 1950–2017 the data is from Penn World Table (PWT) 9.1 (2019). PWT 9.1 sources its working hours data from the Total Economy Database, an updated version of the same source used by Huberman & Minns (TED, 2005).

Further details on the data from Huberman & Minns:
The measure is annual hours of full-time production workers (male and female) in non-agricultural activities. Annual hours are based on estimates of weekly working hours and weeks worked. The data “best approximate usual or normal hours” worked (p. 543).
The original sources are: 1870–1913: Huberman (2004); 1929–1938: ILO (1934–39), except for Canada (Ostry and Zaidi, 1972), U.S. (Jones, 1963; Owen, 1988), and Australia (Butlin, 1977). These sources in turn rely on a variety of primary data sources, particularly establishment surveys and labor force surveys.

Further details on the data from PWT 9.1/TED:
The measure is labeled “Average annual hours worked by persons engaged” (PWT label) and “Average annual hours worked per worker” (TED label). It refers to actual hours worked and is calculated as total annual hours worked divided by persons employed. Annual hours are based on estimates of weekly working hours and weeks worked.
The original sources are National Accounts data when available; when unavailable, other databases (e.g., the Asian Productivity Organization’s Asian Productivity Database) and academic publications are used. For a complete description of primary sources and definitions see TED’s detailed sources and methods guide (https://www.conference-board.org/retrievefile.cfm?filename=TED_SMDetailed_nov2017.pdf&type=subsite)


    