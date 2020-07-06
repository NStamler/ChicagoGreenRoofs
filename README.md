# Chicago Green Roofs Project

## About
### Contributors

## Data
### Monitoring Data
(Filler data from OpenAirQ)
Name | Type | Measured parameter | Spatial resolution | Time resolution | Comments
--- | --- | --- | --- | --- | --- 
AirNow | EPA's sensor network | Criteria pollutants | Sensor location | Hourly data | Limited spatial coverage
AoT | Sensor network | NO2, O3, H2S, CO, SO2, PM (~10% of nodes) | Sensor location | ~30 seconds | Non-calibrated air quality data
AirCasting | Personal monitoring | PM, Sound level, Relative humidity, Temperature | User location (fixed or mobile session) | 1s for mobile session, 1mn for fixed session | Low-cost sensor (non-reliable data)

### GIS Data

Name | Type | Measured parameter | Spatial resolution | Extent | Date Published | Date Last Modified | Source | Comments
--- | --- | --- | --- | --- | --- | --- | --- | ---
USGS 13 arc-second n42w088 1 x 1 degree | USGS Elevation Products (3DEP) - Raster | Elevation | 1/3 arc-second | 1 x 1 degree | 2017-08-24 | 2020-03-03 | [USGS](https://viewer.nationalmap.gov/basic/#productSearch) | Doesn't quite cover the northern tip of Chicago
LC08_CU_021007_20190610_20190621_C01_V01_ST | Provisional Surface Temperature | Land Surface Temperature (LST) - Raster | 30m |  | 2019-06-10 |  | [USGS](https://earthexplorer.usgs.gov/) | Northern half of Chicago
LC08_CU_021008_20190610_20190621_C01_V01_ST | Provisional Surface Temperature | Land Surface Temperature (LST) - Raster | 30m |  | 2019-06-10 |  | [USGS](https://earthexplorer.usgs.gov/) | Southern half of Chicago
LC08_CU_021007_20190712_20190723_C01_V01_ST | Provisional Surface Temperature | Land Surface Temperature (LST) - Raster | 30m |  | 2019-07-12 |  | [USGS](https://earthexplorer.usgs.gov/) | Northern half of Chicago
LC08_CU_021008_20190712_20190723_C01_V01_ST | Provisional Surface Temperature | Land Surface Temperature (LST) - Raster | 30m |  | 2019-07-12 |  | [USGS](https://earthexplorer.usgs.gov/) | Southern half of Chicago
Building Footprints (current) | Chicago building footprints | Shapefile | N/A | N/A | 2015-08-14 | 2018-07-11 | [City of Chicago](https://data.cityofchicago.org/Buildings/Building-Footprints-current-/hz9b-7nh8) | Large file, so a bit slow to process in ArcGIS
Parks - Chicago Park District Park Boundaries (current) | Chicago Park District properties | Shapefile | N/A | N/A | 2015-03-19 | 2019-08-05 | [City of Chicago](https://data.cityofchicago.org/Parks-Recreation/Parks-Chicago-Park-District-Park-Boundaries-curren/ej32-qgdr) |


### Geometry

File Name | Data Type | Description | Date Created | Date Last Modified | Creator | Last Modified By | Comments
--- | --- | --- | --- | --- | --- | --- | --- 
city_hall_outline | Raster (TIF) | City Hall green roof boundaries | Summer 2019 | Summer 2019 | Jacob Abramowitz | Jacob Abramowitz |  |
Millennium_Park | Raster (TIF) | Millennium Park green roof boundaries | Summer 2019 | Summer 2019 | Jacob Abramowitz | Jacob Abramowitz |  |
walmart2_good | Raster (TIF) | City Hall green roof boundaries | Summer 2019 | Summer 2019 | Jacob Abramowitz | Jacob Abramowitz | Possible raster errors |
City Hall | Polygon (Shapefile) | City Hall green roof boundaries | 2019-07-06 | 2019-07-06 | Natasha Stamler | Natasha Stamler | Built off of city_hall_outline |
Millennium Park | Polygon (Shapefile) | City Hall green roof boundaries | 2019-07-06 | 2019-07-06 | Natasha Stamler | Natasha Stamler | Built off of Millennium_Park |
Walmart | Polygon (Shapefile) | Walmart green roof boundaries | 2019-07-06 | 2019-07-06 | Natasha Stamler | Natasha Stamler | Built off of walmart2_good |


## Resources
### Trainings From the University of Chicago GeoDaCenters's [OpenAirQ-phase1](https://github.com/GeoDaCenter/OpenAirQ-phase1)
[NASA Applied Remote Sensing Training](https://arset.gsfc.nasa.gov) (ARSET) program offers satellite remote sensing training that builds the skills to integrate NASA Earth Science data into an agency’s decision-making activities. Trainings are offered in air quality, climate, disaster, health, land, water resources, and wildfire management.
* [Fundamentals of Remote Sensing](https://arset.gsfc.nasa.gov/webinars/fundamentals-remote-sensing)
* [High Temporal Resolution Air Quality Observations from Space](https://arset.gsfc.nasa.gov/airquality/webinars/2018-geospatial)
* [Advanced Webinar: Data Analysis Tools for High Resolution Air Quality Satellite Data Sets](https://arset.gsfc.nasa.gov/airquality/webinars/2018-hiresdatasets)

Array of Things (AoT)
* [Mapping Array of Things (AoT) Data with Spatial Statistics](https://geodacenter.github.io/aot-workshop/)
