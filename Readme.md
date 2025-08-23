# Foot Pressure Distribution Visualizer

An interactive **Streamlit application** for visualizing and analyzing **foot pressure distribution data** collected from sensors.  

The app allows users to upload CSV files with sensor data (L1–L40 for left foot, R1–R40 for right foot) or work with sample data. It then generates **dynamic heatmaps of foot pressure over time**, provides playback controls, screenshots, and generates detailed pressure and balance reports.  

---

## 🚀 Features

- **CSV Upload & Auto-Conversion**  
  Accepts raw data in `L1–L40, R1–R40` format and converts it into `left_0–left_39, right_0–right_39` format.  

- **Interactive Foot Visualization**  
  - Dynamic playback of pressure data across frames  
  - Adjustable playback speed and manual frame slider  
  - Toggle pressure values on/off  

- **Screenshot Export**  
  Save any frame as a `.png` file for reporting or documentation.  

- **Analysis Report**  
  - Peak pressure frame detection  
  - Left vs Right foot dominance  
  - High-pressure alerts (above 80th percentile)  
  - Balance score analysis (0–1 scale)  
  - Downloadable CSV report  

- **Pressure Heatmap Scale**  
  Color-coded visualization from low (white) to high (red).  

---
