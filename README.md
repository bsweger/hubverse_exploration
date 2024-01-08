# *Hubverse Exploration*

This repository was created from a hubverse template, with the goal of exploring the hubverse format and tools.

## *No forecasts at all, really*

**Dates:** The Challenge Period will begin *[insert start date]* and will run until *[insert start date]*. Participants are currently asked to submit *[insert description of forecasts]*  by *[insert timing]* .(herein referred to as the Forecast Due Date). In the event that timelines of data availability change, *[insert name of hub]*  may change the day of week that forecasts are due. In this case, participants would be notified at least one week in advance. *[insert temporal period]*  submissions (including file names) will be specified in terms of the reference date, which is the Saturday following the Forecast Due Date. The reference date is the last day of the epidemiological week (EW) (Sunday to Saturday) containing the Forecast Due Date.

**Prediction Targets:**
Participating teams are asked to provide *[insert geographical requirements]*  predictions for  targets *[insert name of target(s)]*.

Teams will submit  *[insert description of forecasts]* for the epidemiological week (EW) ending on the reference date as well as  *[insert horizons]*. Teams can but are not required to submit forecasts for all *[insert temporal period]* horizons or for all locations. The evaluation data for forecasts will be the *[insert temporal period]* aggregate of *[insert description of evaluation data]*  We will use the specification of EWs defined by the [CDC](https://wwwn.cdc.gov/nndss/document/MMWR_Week_overview.pdf), which run Sunday through Saturday. The target end date for a prediction is the Saturday that ends an EW of interest, and can be calculated using the expression:
**target end date = reference date + horizon * (*[insert # days in temporal period]* days)**.

There are standard software packages to convert from dates to epidemic weeks and vice versa (e.g. [MMWRweek](https://cran.r-project.org/web/packages/MMWRweek/) and [lubridate](https://lubridate.tidyverse.org/reference/week.html) for R and [pymmwr](https://pypi.org/project/pymmwr/) and [epiweeks](https://pypi.org/project/epiweeks/) for Python).


## Acknowledgments
This repository follows the guidelines and standards outlined by the [hubverse]([url](https://hubdocs.readthedocs.io/en/latest/)), which provides a set of data formats and open source tools for modeling hubs.


<mark style="background-color: #FFE331">**As an example, here is the link to [Flusight-Forecast_Hub  README](https://github.com/cdcepi/FluSight-forecast-hub/blob/master/README.md).  **</mark>
