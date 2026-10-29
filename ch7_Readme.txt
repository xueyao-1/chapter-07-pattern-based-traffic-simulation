Input data: trainHH_full_data.csv labeled_data_3000-6000.csv

1_pattern_based_modelling.ipynb: 

- Overview of pattern data: calculate the slope of acceleration for each pattern segment and save data as avg_pattern_data.csv
- plot contour of speed_related patterns, get speedup_slowdown_contour1.pdf, 3Dplot_for_distance_pattern.pdf
- fitting pattern data and get vehicle dynamics models for each pattern

2_pattern-based_simulation.ipynb 

- Heterogeneous traffic flow simulation: 
Get: simulation_summary data, simulation_timeseries data, pattern_name_simulation, and pattern_duration_simulation data under different lambda (alpha and beta) settings.

- Alpha and beta variability: example of driver 5

- Heterogeneity of traffic flow level: game testing

- Disturbance impacts: One vehicle slows down for a long while, calculate the propagation of disturbance and impacts on traffic stability

- Traffic flow impacts: calculate impacts of traffic safety and energy efficiency by changing alpha and beta. 


