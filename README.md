# 🛡️ Cyber Threat Command Center | Power BI Executive Dashboard

## 1. Project Headline
**Production-Grade Cyber Threat Intelligence & SOC Operations Center Built in Power BI**

---

## 2. Description & Purpose
An executive-level, interactive Security Operations Center (SOC) dashboard designed with a high-contrast dark cyberpunk theme (`#121829` Dark Slate, `#00F0FF` Electric Cyan, `#FF007F` Neon Pink). The dashboard unifies raw network session logs into actionable threat intelligence, enabling security analysts and CISOs to monitor live attack vectors, assess protocol vulnerability rates, and track malicious traffic patterns in real time.

---

## 3. Tech Stack
* **Business Intelligence Platform:** Power BI Desktop / Power BI Service
* **Data Transformation & Querying:** Power Query (M Language)
* **Analytics & Calculations:** DAX (Data Analysis Expressions) for custom KPI measures
* **UI/UX Visual Design:** Cyberpunk Grid Layout, Custom Tile Slicers, Card (New) Visuals
* **Version Control & Hosting:** GitHub, Git

---

## 4. Data Source
* **Dataset:** Simulated / Operational Security Information and Event Management (SIEM) Network Logs (`cybersecurity_logs.csv`).
* **Core Entities:** `session_id`, `protocol_type` (TCP, UDP, ICMP), `browser_type`, `failed_logins`, `ip_reputation_score`, and `Attack Status` (Attack vs Normal).

---

## 5. Key Documentation

### Business Problem
Security Operations Centers often struggle with fragmented log data across protocols and browser agents, making it difficult to detect targeted attack vectors quickly. Standard tabular reports lack visual hierarchy, slowing down response times during critical incident triage.

### Goal of the Dashboard
To provide SecOps teams and CISOs with a single, high-impact command interface that accelerates incident detection, visualizes threat density across attack surfaces, and streamlines protocol/browser-level cross-filtering.

### Walkthrough of Key Visuals
* **Top KPI Card Bar:** Displays executive metrics at a glance—`Total Sessions`, `Total Attacks`, `Attack Rate %`, `Total Failed Logins`, and `Avg IP Reputation`.
* **Attacks by Protocol Type (Column Chart):** Compares normal traffic vs. attack volume across `TCP`, `UDP`, and `ICMP` protocols.
* **Attack Vectors by Browser (Donut Chart):** Breaks down intrusion attempts across browser user-agents (`Chrome`, `Firefox`, `Edge`, `Safari`, `Unknown`).
* **Threat Distribution (Treemap):** Hierarchical risk mapping visualizing protocol-and-browser combinations by attack volume.
* **Summary Matrix & Interactive Tile Slicer:** Stretched bottom container offering drillable protocol log metrics side-by-side with interactive custom browser tile filters.

### Business Impact & Insights
* **Rapid Incident Triaging:** Reduces Mean Time to Detect (MTTD) by surfacing high-risk attack vectors on a single screen.
* **Protocol Vulnerability Identification:** Pinpoints `TCP` and `UDP` as primary threat vectors with real-time conditional highlights (`#FF007F` Neon Pink).
* **Operational Efficiency:** Replaces cluttered log tables with drillable matrices and responsive tile filters for instantaneous root-cause analysis.

---

## 6. Screenshots & Media

### 🎬 Video Demo Walkthrough
[![Watch Dashboard Video](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1379).png)](https://github.com/Abdullahprobro/cyber-attack-analytics-powerbi/blob/main/Untitled%20design%20(2).mp4)

---

### 📷 Dashboard Visual Gallery

#### Executive Command Center Overview
![Main Dashboard View](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1379).png)

#### Protocol & Browser Threat Distribution
![Threat Distribution](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1378).png)

#### Interactive Slicer & Matrix Drill-Down
![Matrix and Slicer](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1377).png)

<details>
<summary><b>🔍 View Additional Dashboard Screenshots</b></summary>

| View / Snapshot | Image Link |
| :--- | :--- |
| **KPI Metrics Detail** | ![Screenshot 1376](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1376).png) |
| **Attack Vector Analysis** | ![Screenshot 1375](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1375).png) |
| **Protocol Breakdown** | ![Screenshot 1374](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1374).png) |
| **Interactive Filter State** | ![Screenshot 1373](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1373).png) |
| **Treemap Hierarchy** | ![Screenshot 1372](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1372).png) |
| **Data Model Layout** | ![Screenshot 1371](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1371).png) |
| **Cybersecurity Matrix Grid** | ![Screenshot 1370](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1370).png) |
| **Header Banner Focus** | ![Screenshot 1369](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1369).png) |
| **Initial Concept Grid** | ![Screenshot 1366](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1366).png) |
| **Dark Theme Styling Setup** | ![Screenshot 1365](https://raw.githubusercontent.com/Abdullahprobro/cyber-attack-analytics-powerbi/main/Screenshot%20(1365).png) |

</details>
