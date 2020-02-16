# COVID-19
## References:
* Li, J. (2020). A Robust Stochastic Method of Estimating the Transmission Potential of 2019-nCoV. arXiv preprint arXiv:2002.03828.
* Wu, J. T., Leung, K., &
Leung, G. M. (2020). Nowcasting and forecasting the potential domestic and international spread of the 2019-nCoV outbreak originating in Wuhan, China: a modelling study. The Lancet.
* Imai, N., Dorigatti, I.,Cori, A., Riley, S., & Ferguson, N. M. (2020). Estimating the potential
total number of novel Coronavirus cases in Wuhan City, China. Imperial College London, 17.

## Current Progress:
Feb. 16. 2020
* Prediction_JHK_SEIR.ipyb
1. Update the data with JHK data
2. Apply new parameters
3. Simulating the inflow data(on going)

* <b>R0 option:</b><br>
1. Baseline model is using the parameter from (Li, J. 2020), this model assume the transmission rate, recovery rate are similar<br>
2. R0 could be calculated through MAP process with Poisson Distribution (Wu, J. T. 2020)<br>
3. Another way is to get dynamic beta (beta =R0/gamma gamma: recovery rate) see Wechat https://mp.weixin.qq.com/s/GoExay4zzZQcFL1T0f2OfA<br>
* Need transportation information to further push the model
* Simple solution for large scale simulation: see resource folder <b>预测2020-02-01v2.xlsx</b>, this file only use a sigmoid function, fit the data pretty good.

## Detailed process is in the Jupyter Notebook

## Data is from DXY-COVID-19-Data
