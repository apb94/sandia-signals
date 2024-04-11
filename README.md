# sandia-signals
Background research, relevant sources, basic code. Degradation classification/prediction moving toward application in a system of sensors.

ncmapss_eda looks at sensor profiles over flight cycles
old_cmapss_fpca is basic exploration on old-cmapss as well as some filtering and smoothing examples
fpca_final is PCA for feature space reduction and FPCA regression for most important "phase" of flight
LSTM is reshaping data, building network, fitting model, recording results
lstm2 is LSTM applied to old cmapss (not addressed in paper)
anomaly_detection is autoencoder for early flight anomalies
flight_profile is using the profile variables to predict RUL and then calculating "excess RUL" on different routes
3DLSTM is trying to target RUL as well as HPT/LPT
