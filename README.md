# metroPT3
MetroPT-3 veri seti üzerinde öznitelik mühendisliği, Isolation Forest ve PyTorch LSTM Autoencoder ile denetimsiz anomali tespiti.

MetroPT-3 Predictive Maintenance & Anomaly DetectionBu proje, UCI MetroPT-3 veri seti kullanılarak kentsel metro hava üretim ünitelerindeki (APU/kompresör) mekanik, termal ve pnömatik arızaları (hava kaçağı, kule tıkanması, valf kilitlenmesi) erken aşamada tespit etmek amacıyla geliştirilmiştir.   Çözüm; alan bilgisine dayalı fiziksel türev ve fark hesaplamalarını (domain-specific feature engineering), zaman serisi kayan pencerelerini (sliding window) ve denetimsiz öğrenme mimarilerini (Isolation Forest & PyTorch LSTM Autoencoder) içerir. 
