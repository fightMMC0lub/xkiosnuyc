# ⚙️ OSSIM Workflow

| 🧩 Step                  | 📋 Description                                           | ⚡ Purpose                                                   |
|--------------------------|-----------------------------------------------------------|---------------------------------------------------------------|
| **1. Data Collection**   | Sensors, agents, and plugins collect logs & events from servers, firewalls, IDS, etc. | Gather raw security data from all parts of the network         |
| **2. Normalization**     | Collected data is converted into a unified format          | Make all logs and events understandable by the SIEM system     |
| **3. Correlation**       | The correlation engine links related events together       | Detect attack patterns and reduce false positives               |
| **4. Detection & Alerts**| Suspicious patterns trigger alarms                         | Notify security teams of potential incidents                    |
| **5. Analysis**           | Analysts review alerts, investigate root causes            | Understand the scope and impact of detected threats             |
| **6. Response & Reporting** | Actions taken (block IP, patch, isolate host) and reports generated | Contain the threat, fix issues, and document the incident       |
