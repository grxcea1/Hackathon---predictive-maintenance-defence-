# Hackathon---predictive-maintenance-defence-
AI-powered predictive maintenance system for UAVs, built for the European Defense Tech Hackathon. Our prototype processes UAV flight logs, detects anomalies using machine learning, predicts failures before they happen, and provides explainable maintenance alerts through a simple dashboard.


Predictive Maintenance for UAVs
European Defense Tech Hackathon Project
Overview

This project was created during the European, where our challenge was to explore predictive maintenance for unmanned aerial vehicles (UAVs).Our idea is to build an AI-powered early warning system that can learn from UAV flight logs, spot unusual behavior, and flag potential issues before they turn into real failures. The end goal is to help operators keep UAVs safe, reliable, and mission-ready with minimal downtime.

What It Does
Reads and processes UAV sensor logs (ESC, IMU, barometer, GPS, etc.) in CSV or binary format
Uses machine learning and anomaly detection techniques to identify when something looks unusual
Labels flights as normal or at risk, while pointing out likely causes (for example: motor overheating or strange vibration patterns)
Produces clear, explainable alerts so operators know what’s happening and what to check

Tech Stack
Python – data man
Scikit-learn / PyT
Matplotlib / Plotly – graphs and visualizations

Hackathon Goal:
Our prototype will Highlight and show results in a simple dashboard with alerts and visual explanations

Future Ideas:
If we had more time, we’d like to extend this project with:
1-Real-time analysis 
2-More explainability (using tools like SHAP or LIME to show why the model flagged an issue)
