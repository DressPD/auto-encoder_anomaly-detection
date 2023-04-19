# auto-encoder_anomaly-detection

auto encoder model for anomaly detection of logs.  
this algorithm/process is made to detect failure originates in ESB, hosts and traces files.

Data templates are provided for reproducibility and code adaptation.  
After exploratory data analysis, an auto-encoder model is deveoped trying to identify anomalies bases on a threshold higher than max MAE metric.

Afterwards, selected traces in a defined time interval are classified based on time differences and root cause of failure is determined.

Considering the simplicity of the model, it requires soma manual analysis or improvements to perform automated analysis. Nevertheless, it's a good starting point for tuning and development.

