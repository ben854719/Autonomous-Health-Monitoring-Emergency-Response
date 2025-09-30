## Autonomous Health Monitoring Emergency Response

## Objective:

This application uses Bluetooth technology to connect the worker’s smartphone to the supervisor’s laptop, enabling real-time health monitoring via multimodal data. PySyft ensures encrypted biometric authentication with high accuracy and privacy protection. A machine learning model tracks fatalities and injury levels, visualized through a Matplotlib dashboard. When thresholds are breached, agentic AI triggers emergency protocols, recommends actions, and automatically initiates a 911 response with location and incident details. Target KPIs include 95% detection precision, 40% faster emergency response, and zero biometric data leakage.

## Video of the project:


## Features:

## Privacy-Preserving Biometric Authentication:

- Uses PySyft to verify worker identity securely and privately.
- Ensures encrypted biometric processing with no raw data exposure.

##  Bluetooth-Based Health Monitoring:

- Connects smartphone to supervisor laptop via Bluetooth.
- Streams real-time multimodal data (biometric, behavioral, environmental).

## Machine Learning Health Assessment:

- Built with PyTorch, Pandas, and NumPy for detecting stress and injury indicators.
- Tracks biometric anomalies and environmental exposure trends.

## Real-Time Dashboard Visualization:

- Displays live health metrics using Matplotlib.
- Visualizes stress index, injury risk score, and biometric signal patterns.

## Agentic AI Emergency Protocols:

- Implements autonomous decision-making using LangGraph and Agentic AI.
- Triggers emergency actions when thresholds are breached.
- Recommends appropriate protocols based on worker condition.

## Secure Communication & Control:

- Uses Socket.io for real-time bidirectional updates.
- Centralized coordination via MCP Server for policy enforcement and alert routing.

##  Natural Language Interaction:

- Integrates Gemini for supervisor-friendly explanations and voice alerts.
- Enables intuitive interaction with AI decisions and health summaries.

## Installation:


