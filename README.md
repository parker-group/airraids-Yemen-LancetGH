# airraids-Yemen-LancetGH
This repository contains two datasets: ModelVars.csv and AirRaidsAggs.csv.

## ModelVars.csv
This dataset contains information on conflict-related, environmental, demographic, economic, and spatial variables per Yemen governorate between 2016 - 2019. Aid raids are compiled into rolling 3 month aggregations with no lag. 


**Data Sources**

Case and population data: [Simpson RB, Babool S, Tarnas MC, Kaminski PM, Hartwick MA, Naumova EN. Signatures of Cholera Outbreak during the Yemeni Civil War, 2016–2019. Int J Environ Res Public Health 2021; 19: 378](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8744546/)

Air raids: [Yemen Data Project](https://yemenlg.org/governorates/)

Precipitation and temperature: [World Bank Climate Change Knowledge Portal](https://climateknowledgeportal.worldbank.org/)

NDVI and surface water: [NASA MODIS Data](https://modis.gsfc.nasa.gov/data/) downloaded via [NASA’s Application for Extracting and Exploring Analysis Ready Samples](https://appeears.earthdatacloud.nasa.gov/)

Economic variables: World Food Program Monthly Market Watch Bulletins for [2016](https://www.wfp.org/publications/yemen-monthly-market-watch-2016), [2017](https://www.wfp.org/publications/yemen-monthly-market-watch-2017), [2018](https://www.wfp.org/publications/yemen-monthly-market-watch-2018), and [2019](https://www.wfp.org/publications/yemen-monthly-market-watch-2019)


## AirRaidsAggs.csv
This dataset contains different aggregations of air raids with varying lags. For each aggregation and lag combination, we included a numerical sum of air raids and the corresponsing category (Low, Intermediate, Medium, High, or Severe) based on quintiles for that specific aggregation. These aggregations were all rolling. We chose the 3 month aggregation with no lag based on model fit.

Commercial use of either dataset is strictly prohibited.
