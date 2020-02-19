# COVID-19
## References:
* Li, J. (2020). A Robust Stochastic Method of Estimating the Transmission Potential of 2019-nCoV. arXiv preprint arXiv:2002.03828.
* Wu, J. T., Leung, K., &
Leung, G. M. (2020). Nowcasting and forecasting the potential domestic and international spread of the 2019-nCoV outbreak originating in Wuhan, China: a modelling study. The Lancet.
* Imai, N., Dorigatti, I.,Cori, A., Riley, S., & Ferguson, N. M. (2020). Estimating the potential
total number of novel Coronavirus cases in Wuhan City, China. Imperial College London, 17.

## Current Progress:
Feb. 18. 2020
<b>Simulating the Epidemic Process with estimated flow between provinces.</b><br>
Current Parameters: 
* alpha: The rate at which an exposed person becomes infective. 1/7
* beta: The parameter controlling how often a susceptible-infected contact results in a new exposure.  0.65
* gamma:The rate an infected recovers and moves into the resistant phase.0.135
* R0:beta/gamma
* Mobility Factor: 85% meaning 85% of the peak flow between governments
* Simulation Starts with assumption: Hubei has one person get exposed to the virus at Day 1.

* total population: 2018 census
* flow matrix between cities: simulation


<b>Next Steps:</b>
1. Create Dashboard layout
2. Change point csv to polygon file, represent the polygon with color gradient
3. Compare the real update and the simulation data
4. Highlight the key moment in this whole event
5. How to add hospital related factor?




## Current Visualization: output/kepler.html (drag the time bar to see the transition)
## Side insights: https://observablehq.com/@yuanzf/seir

## Data is from DXY-COVID-19-Data
