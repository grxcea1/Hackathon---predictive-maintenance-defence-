# Predictive Maintenance Challenge

AI-powered predictive maintenance system for UAVs, built for the **European Defense Tech Hackathon**. Our prototype processes UAV flight logs, detects anomalies using machine learning, predicts failures before they happen, and provides explainable maintenance alerts through a simple dashboard.

---

## Project Overview

This project was created for the European Defense Tech Hackathon, where the challenge was to explore **predictive maintenance for unmanned aerial vehicles (UAVs)**. Our idea was to build an AI-powered early warning system that can:

- Learn from UAV flight logs
- Spot unusual behavior
- Flag potential issues before they turn into real failures  

The goal is to help operators keep UAVs **safe, reliable, and mission-ready** with minimal downtime.

---

## What It Does

- **Reads and processes UAV sensor logs** (ESC, IMU, barometer, GPS, etc.) in CSV or binary format  
- **Uses machine learning and anomaly detection** techniques to identify unusual behavior  
- **Labels flights as normal or at risk**, highlighting likely causes (e.g., motor overheating or abnormal vibration patterns)  
- **Produces clear, explainable alerts** so operators know what’s happening and what to check  

---

## Tech Stack

- **Python** – data management and processing  
- **Scikit-learn / PyTorch** – machine learning and anomaly detection  
- **Matplotlib / Plotly** – graphs and visualizations  

---

## Hackathon Goal

Our prototype showcases results in a **simple dashboard** with:

- Alerts for potential failures  
- Visual explanations of anomalies  

---

## Future Ideas

If we had more time, we’d like to extend this project with:

1. Real-time analysis  
2. Enhanced explainability using tools like **SHAP** or **LIME** to show why the model flagged an issue  
