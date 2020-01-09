# U.S. Skin Cancer Analysis _2012-2016_
Granularity: _US Counties_

_Skin Cancer Incidence_ is defined as the number of new melanomas occuring in a specified population during a year.

## Project Goals

The goal of this project is to investigate the incidence of melanoma throughout U.S. counties. Furthermore, it is valuable to run a two tailed z-test on the counties that have high UV exposure and those that have high incidences of melanoma as well as those counties that have low UV exposure and those that have low incidences of melanoma. This could either prove or disprove that living in counties that have high UV exposure could lead to higher incidences of melanoma and vice versa.

## Pipeline
I have downloaded the data as .txt & .csv files, read it into my jupyter notebook, and started to parse out meaningful statistics such as the mortality and incidence rates for each race, gender, and zip code as well as the totals.

Using REGEX to extract FIPS codes and created a choropleth map of the population of cancer per county.

I have joined the two tables of UV rates and Cancer Stats so that now I can perform statistical operations and create choropleth maps of cancer per county, and with respect to race and sex.

## Statistics of Interest

Between the years of __2012-2016__, the US national average rate of melanoma incidences is about __28__ out of every 100,000 people. 

The highest observed rate of melanoma incidences is in Towns County, Georgia at about __89__ out of every 100,000 people; __316%__ above the national average.

The 10 counties with the highest incidence rates of melanoma are:
1. Towns County, GA           (__89.2__ people per 100,000)
2. Beaver County, Utah        (__83.9__ people per 100,000)
3. Pickens County, GA         (__83.0__ people per 100,000)
4. Ouray County, CO           (__78.4__ people per 100,000)
5. Summit County, UT          (__77.8__ people per 100,000)
6. Sarasota County, FL        (__77.1__ people per 100,000)
7. Jefferson County, WA       (__74.1__ people per 100,000)
8. Cape May County, NJ        (__73.6__ people per 100,000)
9. Union County, GA           (__73.3__ people per 100,000)
10. Marin County, CA          (__72.3__ people per 100,000)

These findings are consistent with U.S. Census Data which between the years of 2007-2011 said that these states were the top 10 in incidences of melanoma:

1. Utah
2. Vermont
3. Delaware
4. New Hampshire
5. Oregon
6. Minnesota
7. Washington
8. Idaho
9. Kentucky
10. Kansas

The lowest observed rate of melanoma incidences is in Webb County, Texas at about __2__ out of every 100,000 people; __93%__ lower than the national average.

The 10 counties with the lowest incidence rates of melanoma are:
1. Webb County, TX            (__2.0__ people per 100,000)
2. Hidalgo County, TX         (__4.1__ people per 100,000)
3. Bronx County, NY           (__4.1__ people per 100,000)
4. Cameron County, TX         (__5.7__ people per 100,000)
5. El Paso County, TX         (__5.7__ people per 100,000)
6. Prince George's County, MD (__5.7__ people per 100,000)
7. Lea County, NM             (__5.8__ people per 100,000)
8. McKinley County, NM        (__6.9__ people per 100,000)
9. Clayton County, GA         (__7.1__ people per 100,000)
10. Apache County, AZ         (__7.2__ people per 100,000)

## UV Exposure Questions





## Visualizations





## Considerations/Issues
There were a number of U.S. counties that did not have melanoma rates or melanoma rates with regards to certain races. This is likely due to two reasons:

1. The U.S. Census claims to cover 100% of the population, however they admit that certain states and counties suppress their statistics for the following reasons:
  - Fewer than 16 cases were  reported in a specific category
  - State requests for suppression with regard to race & ethnicity
  - "Male" or "Female" counts are suppressed if the counterpart sex "Female" or "Male" is suppressed.
  - Lack of reporting

2. Melanoma has an average rate of about __28__ people per 100,000, which is relatively rare, indicating that incidences of melanoma may not occur in a year for some counties.


# Conclusions




# Future Directions
- Racial considerations 
