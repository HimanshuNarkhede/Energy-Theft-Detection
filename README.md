# Energy Theft Detection System ⚡

Detect suspicious or anomalous electricity consumption using smart meter data.

## 🧠 Techniques Used
- Unsupervised ML: Isolation Forest, DBSCAN
- Anomaly detection based on hourly usage patterns

## 📊 Dataset Features
- `avg_hourly_usage_kwh`
- `max_hourly_usage_kwh`
- `night_usage_ratio`

## 📈 ML Workflow
- Preprocessing: handle outliers, normalize
- Train Isolation Forest & DBSCAN to detect unusual consumption
- Visualize anomalies using scatter plots

## 🛠️ How to Run
1. Open `energy_theft_detector.ipynb` in Jupyter or Colab
2. Install requirements: `pip install -r requirements.txt`
3. Run all cells to detect and visualize flagged consumers
