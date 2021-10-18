# fpp3-package-exploration

**What:**  This is an individual project to explore the fpp3 package functionality


**Data:** This uses the vic_elec dataset which is in library tsibble.  The dataset contains a time series of electrical demand of Victoria, Australia and temperature recordings of Melbourne, Australia for every half an hour period in the years 2012-2014

**What is forecast: ** 
In this file, we look at the time series in an annual view as well as a weekly view and perform regression model forecasting.  In the annual view of the data, we will forecast the demand for electricity in Victoria Australia for the beginning of the following year.  This is interesting because the relationship between electricity demand and temperature is non-linear.  In the weekly view of 30 minute periods, we will use linear forecasting to obtain the demand for electricity in the very next 30 minute time frame based on temperature. 

**More about the data:**
"This data is for operational demand, which is the demand met by local scheduled generating units, semi-scheduled generating units, and non-scheduled intermittent generating units of aggregate capacity larger than 30 MW, and by generation imports to the region. The operational demand excludes the demand met by non-scheduled non-intermittent generating units, non-scheduled intermittent generating units of aggregate capacity smaller than 30 MW, exempt generation (e.g. rooftop solar, gas tri-generation, very small wind farms, etc), and demand of local scheduled loads. It also excludes some very large industrial users (such as mines or smelters)."
