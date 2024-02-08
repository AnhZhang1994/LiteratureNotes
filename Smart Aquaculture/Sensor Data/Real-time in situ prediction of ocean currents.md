# [Real-time in situ prediction of ocean currents](https://www.sciencedirect.com/science/article/pii/S0029801821003577?casa_token=W8PS9HVc1ZMAAAAA:PSJHaH57KWsIH7I1SgviTY2GxkwWTJvG48dnXptP4qFaz8jtxwoDCYMC9AwoaYb-Lf5Dv9mkAQh7)

Journal: Ocean Engineering (Q1)

## Abstract
Deep autoregressive networks (LSTM and Transformer) can predict ocean currents in real-time at any location in the world.

## Data 
Ocean current data at 831 sites (222 stations have data length greater than 2 months) from [NOAA](https://tidesandcurrents.noaa.gov/cdata/StationList?type=Current+Data&filter=historic). Sampling interval: 6 or 10 min

## Conclusion
LSTM and Transformer can predict ocean currents in real-time at any location in the world and even better than traditional Harmonic Method.

e.g., Comparison of speed Normalized Root Mean Squared Error (NRMSE) (lower is better)
| Station ID | Depth (ft) | LSTM | TF  | HM  |
|------------|------------|------|-----|-----|
| hb0401     | 15.7       | 0.14 | 0.12| 0.12|
| jx0302     | 29.5       | 0.1  | 0.09| 0.33|
| jx0701     | 15         | 0.09 | 0.10| 0.12|
| cb0701     | 13.9       | 0.18 | 0.19| 0.2 |
