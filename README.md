# fly-trajectory-mining
A fighter fly out trajectory time series data mining demo, I use agnes and k-means to clustering the flyout data samples into left, straight and right categories. This app includes a fly out trajectory generation program which was developed by matlab and simulink 


To dude Sun Yang:
______________________________


'mts-air-maneuvering-samples-1000-txt-form.txt' time series data description.
 we have 1000 time series, each serie have 0-9 sample points by every second, so 1000*10=10000, then the data set have 10000 rows.
 each record in 1 second was composed as below:
 
 x | y | z | y_global_load_factor | time_in_seconds