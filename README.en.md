# This document was originally created by 
COVID-19/2019-nCoV Time Series Infection Data Warehouse

[简体中文](README.md) | English

COVID-19/2019-nCoV time series infection data warehouse, the data source is [Ding Xiang Yuan](https://3g.dxy.cn/newh5/view/pneumonia).

**Researchers**  
Recently, many college teachers and students contacted me, 
hoping to use these data for scientific research. 
However, not everyone is familiar with the use of APIs and the format of JSON, 
so here is the [data warehouse](https://github.com/BlankerL/DXY-COVID-19-Data) 
to publish the latest data in CSV format, 
which can be easily processed and loaded by most software.

The data is obtained by [COVID-19 Infection Data Realtime Crawler](https://github.com/BlankerL/DXY-COVID-19-Crawler). 
The data will be published hourly. 

#### CSV File List
1. Overall Data [DXYOverall.csv](csv/DXYOverall.csv)
2. Regional Data [DXYArea.csv](csv/DXYArea.csv)
3. News [DXYNews.csv](csv/DXYNews.csv)
4. Rumors [DXYRumors.csv](csv/DXYRumors.csv)

### paper resource: 
Wu, J. T., Leung, K., &
Leung, G. M. (2020). Nowcasting and forecasting the potential domestic and
international spread of the 2019-nCoV outbreak originating in Wuhan, China: a
modelling study. The Lancet.
Imai, N., Dorigatti, I.,
Cori, A., Riley, S., & Ferguson, N. M. (2020). Estimating the potential
total number of novel Coronavirus cases in Wuhan City, China. Imperial College London, 17.


## Data Description
1. As mentioned in [Issue #21](https://github.com/BlankerL/DXY-COVID-19-Data/issues/21), 
Some data are duplicated. For example, in Henan Province, 
there is a city-level document recording Nanyang (Dengzhou inclusive) and Dengzhou.
Therefore, the data of "Dengzhou" will be double-counted once during the summation.



### Packages
1. If you would like to analyze the data with [R](https://www.r-project.org/),
you can refer to [pzhaonet/ncovr](https://github.com/pzhaonet/ncovr).
This project will help you to directly load data into R from either GitHub Data Warehouse or API. 

