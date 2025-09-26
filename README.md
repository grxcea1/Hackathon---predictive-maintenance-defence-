# Hackathon---predictive-maintenance-defence-
AI-powered predictive maintenance system for UAVs, built for the European Defense Tech Hackathon. Our prototype processes UAV flight logs, detects anomalies using machine learning, predicts failures before they happen, and provides explainable maintenance alerts through a simple dashboard.


Predictive Maintenance for UAVs

European Defense Tech Hackathon Project

Overview

This project was created during the European Defense Tech Hackathon, where our challenge was to explore predictive maintenance for unmanned aerial vehicles (UAVs).

Our idea is to build an AI-powered early warning system that can learn from UAV flight logs, spot unusual behavior, and flag potential issues before they turn into real failures. The end goal is to help operators keep UAVs safe, reliable, and mission-ready with minimal downtime.

What It Does

Reads and processes UAV sensor logs (ESC, IMU, barometer, GPS, etc.) in CSV or binary format

Uses machine learning and anomaly detection techniques to identify when something looks unusual

Labels flights as normal or at risk, while pointing out likely causes (for example: motor overheating or strange vibration patterns)

Produces clear, explainable alerts so operators know what’s happening and what to check

The

Python – data handling and machine learning

Pandas / NumPy – preprocessing and feature extraction

S

Matplotlib / Plotly – graphs and visualizations

Streamlit / Flask (optional) – quick interactive dashboard for demo

D

We’re working with UAV flight logs (CSV/binary) provided during the hackathon. These are used to train our model and to test how well it spots problems.

Hackathon

Our prototype will:

Take in UAV flight logs

Highlight anomalies and predict possible failures

Show results in a simple dashboard with alerts and visual explanations

Future Ideas

If we had more time, we’d like to extend this project with:

Real-time analysis of live UAV data streams

More explainability (using tools like SHAP or LIME to show why the model flagged an issue)
