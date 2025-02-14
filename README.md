# 🚦 Urban Traffic Noise Impact Analysis Using Biosensors  

## 📌 Project Overview  
This project investigates how urban traffic noise affects human health using **wearable biosensors**. Instead of just measuring noise levels in decibels (dB), we analyze **real-time physiological responses** such as heart rate variability (HRV) and stress indicators to understand the impact of noise pollution.  

## 🎯 Key Objectives  
- Measure and map urban traffic noise levels.  
- Analyze **physiological responses** (heart rate, HRV, stress) using biosensors.  
- Identify the **threshold noise levels** that significantly affect health.  
- Provide insights for **urban planning and noise pollution policies**.  

## 🛠️ Technologies Used  
- **Python** (for data processing and analysis)  
- **Pandas, NumPy** (data handling)  
- **Matplotlib, Seaborn** (visualization)  
- **Biosensors**: MAXREFDES104# Health Sensor  
- **USB Noise Data Logger** (for noise level recording)  


## 🔬 Methodology  
1. **Data Collection**  
   - Noise levels were recorded at different urban locations (50 dB, 60 dB, 70 dB).  
   - Participants wore **biosensors** to measure **heart rate, HRV, stress levels**.  
   - Data was collected in **controlled (simulated noise) and real-world environments**.  

2. **Data Processing & Analysis**  
   - Preprocessing: Cleaning biosensor and noise data.  
   - Feature Extraction: Calculating **HRV metrics (RMSSD, SDNN, LF/HF Ratio)**.  
   - Statistical Analysis: Identifying correlations between noise levels and stress.  
   - Visualization: **Box plots, heatmaps, and violin plots** for insights.  

3. **Findings**  
   - Higher noise levels (70+ dB) **increase stress and heart rate**.  
   - **Real traffic noise** has a stronger impact than simulated noise.  
   - **Threshold noise level: 60 dB**, beyond which significant health effects occur.
   
## 🏙️ Real-World Applications  
- Helps **city planners** design quieter urban spaces.  
- Supports **government policies** on noise control.  
- Enables **health research** on noise-induced stress.  

## 🚀 How to Use This Repository  
1. Clone the repository:  
   ```bash
   git clone https://github.com/anirudhxchaturvedi/Urban-Traffic-Noise-Impact-Analysis-Using-Biosensors.git
   cd Urban-Traffic-Noise-Impact-Analysis-Using-Biosensors
