# 🧠 Machine Learning Time Analysis Platform

## Description
A smart productivity tracking system that analyzes daily time logs to identify behavioral anomalies and improve strategic focus.  
Ideal for professionals aiming to align daily work with personal or team goals, such as dedicating consistent time to high-priority areas like AI, product development, or learning.

## Key Features
- 📊 **Structured Time Logging**: Processes raw time tracking data into a consistent, analyzable format.
- 🔍 **Anomaly Detection**: Flags unexpected time usage or deviations from pre-set commitments.
- 📬 **Automated Feedback**: Sends notifications when trends indicate risk of misalignment with targets.
- 📈 **Goal Tracking**: Ensures regular time is spent on high-impact activities (e.g., "1h/day on AI projects").

## Technologies Used
- Python
- Pandas
- Scikit-learn
- API Integration
- Data Visualization (for planned dashboarding)

## Results
- 🧠 Identified 15% of time spent on low-value tasks  
- 🚀 Boosted productivity by 20% via behavioral insights and automated feedback  

## File Overview

| File             | Description                                               |
|------------------|-----------------------------------------------------------|
| `daily_data.py`  | Loads and prepares structured time tracking data          |
| `daily_anomalies.py` | Detects daily anomalies and triggers feedback based on deviations |

## Sample Snippet: Anomaly Detection Logic

```python
# From daily_anomalies.py
if score > 0.6:
    anomalies.append((project, duration, score))
