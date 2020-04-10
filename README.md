
# Social distancing effects on the environment





## Table of Contents

Background (social distancing, air quality environmental metrics)

Data (source, hypothesis) 

Analysis (t-test, location differences) 

Discussion




### Background

In response to the COVID19 pandemic, governments are enacting social distancing guidelines to slow the spread of the virus.  This study investigates the environmental impact of social distancing with a focus on air quality effects.  Due to social distancing, there has been a decline in motor vehicle and airplane transportation, both major carbon producers as they rely on fossil fuel combustion.  

Air quality is measured looking a number of metrics including carbon monoxide (CO), ozone (O3), sulfur dioxide (SO2), nitrogen dioxide(NO2), lead pollution, and particle pollution. The EPA has set the following levels for air pollutants according to the Clean Air Act as follows.

| Pollutant       | Level*           | average time exposure  |
| ------------- |:-------------:| -----:|
| carbon monoxide (CO)    | 9 ppm | 8 hrs |
| lead (Pb)      | 0.15 ug/m3      |   rolling 3 mo. average |
| nitrogen dioxide (NO2) | 100 ppb      |    1 hr |
| O3 | 70 ppb      |    8 hr |
|   Particle pollution (PM2.5) | 35 ug/m3      |    24 hr |
 |   Particle pollution (PM10) | 150 ug/m3      |    24 hr |
 |   Sulfur dioxide | 75 ppb     |    1 hr |

*https://www.epa.gov/criteria-air-pollutants/naaqs-table

Nitrogen dioxide (NO2) is a byproduct of burning fossil fuels such as from emissions from cars, trucks, buses, power plants, and airplanes.  It forms through a two-step process .  At elevated temperatures during combustion, N2 is oxidized forming an intermediate, nitric oxide (NO) – (eqn 1). In an oxygen-rich environment, nitric oxide further oxidizes to NO2. (eqn 2)

                                             O2 + N2 → 2 NO 		(1)

                                             2 NO + O2 → 2 NO2	 	(2)


Elevated levels of NO2 are known to cause respiratory problems for individuals, particularly those with asthma. As far as environmental effects, NO2 causes acid rain and decreased visibility due to regional haze.

### Data

This study examines the following question:

**Is there a difference in NO2 concentration levels since social distancing measures started?**

Air quality data were collected from the WA Dept of Ecology.
https://fortress.wa.gov/ecy/enviwa/

Here's a snapshot of the data:
![t-test](https://github.com/b-weintraub/social-distancing/blob/unpolluted/images/data_snapshot_all_dates.png)


### Analysis
![t-test](https://github.com/b-weintraub/social-distancing/blob/unpolluted/images/NO2-conc-time-series.png)
![t-test](https://github.com/b-weintraub/social-distancing/blob/unpolluted/images/2020_time_series_plot.png)

Specifically, concentration values from March 2019 and March 2020 were compared to see if they difference were statistically significant. 

Null hypothesis:
Ho = There is no difference in NO2 values between March 2019 and March 2020.

Alternative hypothesis:
Ha= NO2 values are comparatively less during March 2020.


![t-test](https://github.com/b-weintraub/social-distancing/blob/master/images/t-test.png)

A p-value of 0.008 was found from the t-test.  With a 0.05 alpha threshold, the null hypothesis is rejected.

### Discussion
(Take Away, Final Thoughts, Future-steps)
