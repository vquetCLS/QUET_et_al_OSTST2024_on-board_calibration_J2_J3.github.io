# Assessing the use of on-board calibration to unbiased the sigma0 estimated by Jason-2 and Jason-3 missions on geophysical parameters

## Intro

The $\sigma_{0}$ measure is multplied (added in dB) with a coefficient depending on the CAG CODE associated with each measure.

This coefficient is affected with a drift (measured with a serie of calibration campaigns), and this drift depends on the CAG CODE (see following figures for Jason-2 and Jason-3).
Each calibration campaign is realized with a normalized bias. There are no information regarding the possible temporal evolution of this bias.
Temperature variations can also affect measures obtained during those calibration campaigns. This is a source of uncertainty regarding the drift coefficient computed for each CAG CODE.

![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_coef_sig0_j3_poster.png?raw=true)

![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_coef_sig0_j2_poster.png?raw=true)

![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/lin_coef_wrt_cagcodes_poster.png?raw=true)

This drift affects the measurement of the $\sigma_{0}$ and geophysical parameters such as wind speed (directly deduced from $\sigma_{0}$ measurements) and sea level anomaly (through the estimation of the sea state bias and the ionospheric correction).

## Impact at the global scale

The impacts at the global scale of those drifts on $\sigma_{0}$, wind speed and sea level anomaly are illustrated in the following figures for both missions.

Impact on the $\sigma_{0}$:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_sig0_both_missions.png?raw=true)

Impact on the Wind Speed:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_wind_speed_both_missions.png?raw=true)

Impact on the Sea Level Anomaly:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_sla_both_missions.png?raw=true)



## Impact at the regional scale

The impacts at the regional scale of those drifts on $\sigma_{0}$, wind speed and sea level anomaly are illustrated in the following figures for both missions.

Impact on the $\sigma_{0}$:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_reg_sig0_poster.png?raw=true)

Impact on the Wind Speed:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_reg_windspeed_poster.png?raw=true)

Impact on the Sea Level Anomaly:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_reg_sla_poster.png?raw=true)


## Impact at the meso scale

Impact on meso scale performances (differences at monomission crossover points)
On Jason-2:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/meso_scale_j2_poster.png?raw=true)

On Jason-3:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/meso_scale_j3_poster.png?raw=true)

## Impact on the GMSL parameters' (trend and acceleration)

Imapct on the reference GMSL parameters' (trend and acceleration):
Trend:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/triangles_trend_poster.png?raw=true)

Acceleration:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/triangles_acceleration_poster.png?raw=true)


## What about the adaptive retracker ? 

Impact on the $\sigma_{0}$:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_sig0_j3_adaptive.png?raw=true)

Impact on the Wind Speed:
![alt text](https://github.com/vquetCLS/QUET_et_al_OSTST2024_on-board_calibration_J2_J3.github.io/blob/main/drift_wind_speed_j3_adaptive.png?raw=true)


## What about Jason-1 ?

No similar investigation were implemented on Jason-1. 
It could be interesting to check, but there are currently no available data to perform similar analysis.
