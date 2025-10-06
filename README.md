## Autonomous Health Monitoring Emergency Response

## Objective:

This application uses Bluetooth technology to connect the worker’s smartphone to the supervisor’s laptop, enabling real-time health monitoring via multimodal data. PySyft ensures encrypted biometric authentication with high accuracy and privacy protection. A machine learning model tracks fatalities and injury levels, visualized through a Matplotlib dashboard. When thresholds are breached, agentic AI triggers emergency protocols, recommends actions, and automatically initiates a 911 response with location and incident details. Target KPIs include 95% detection precision, 40% faster emergency response, and zero biometric data leakage.

## Video of the project:

[YouTube](https://youtu.be/bpwXIqEOBk4)

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

- Uses Socket for real-time bidirectional updates.
- Centralized coordination via MCP Server.

##  Natural Language Interaction:

- Integrates Gemini for supervisor-friendly explanations and alerts.
- Enables intuitive interaction with AI decisions and health summaries.

## Installation:

## Prerequistes:

- Cryptography
- Python
- PyTorch
- Pandas
- Bluetooth-enabled smartphone and laptop
- Numpy
- NLTK
- Matplotlib
- PySyft
- LangGraph
- Gemini
- Agentic AI
- Socket Server
- MCP Server
- TCP
- Tenseal

## Python: Required all Major Components.

- Cryptography
- PyTorch
- Matplotlib
- Numpy
- Pandas
- NLTK

## Bluetooth Requirement:

- Smartphone: Android or iOS with Bluetooth.
- Laptop (Windows/IOS).

## Socket Requirement:

- Useful for sending sensor data between the smartphone and the laptop over Wi-Fi.

## PySyft Requirement:

- Enable privacy-preserving machine learning by simulating secure data domains, encrypted tensor sharing, and federated workflows.
- Perfect for biometric authentication systems.

## Agentic AI Configuration (with MCP Server Installation):

## API Credentials:

- Register and obtain your Gemini API key from Google AI Studio.
- Store the key securely in a .env file to protect sensitive credentials.
  
##  LangGraph Workflow: Emergency Protocol & 911 Escalation:

## This flow enables agentic AI:

- Monitor multimodal inputs.
- Detect emergencies based on thresholds or anomaly patterns.
- Recommend context-aware actions.
- Automatically initiate a 911 response with location and incident metadata.

## Normalize:

- Clean and standardize the input text.

## Detect:

- Identifies user intent.
- Detects input language for routine or fallback.
- Enables smart branching in LangGraph.

## Fallback:

- Input is malformed or ambiguous.
- Language or intent cannot be confidently detected.
- Emergency detection fails or yields uncertain results.
- Location or escalation services are unavailable.

## Output:

- Deliver the final result of the emergency detection flow.
- including incident metadata, recommended actions, and escalation status.

## Data Referral:

- Dataset title: Occupational Health and Safety work fatality and critical injury counts report.
- Links: https://open.canada.ca/data/en/dataset/f3e63186-8401-4c9e-a490-1f9e7d7eb00b

- Dataset title: CCOHS
- Links: https://www.ccohs.ca/oshanswers/legisl/legislation/injury_reporting.html

- Dataset title: Ontario Beginning Construction of Highway 413
- Link: https://news.ontario.ca/en/release/1006370/ontario-beginning-construction-of-highway-413

- Dataset title: Ontario Provincial Police
- Links: ttps://www.opp.ca/index.php?id=125


  

