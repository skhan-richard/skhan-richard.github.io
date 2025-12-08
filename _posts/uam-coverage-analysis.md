---
title: High-Fidelity UAM Communication Analysis: Simulator Development and Real-Terrain Optimization
date: 2025-08-10 10:00:00 +0900
categories: [Research, UTM/UAM Communication]
tags: [UTM, Redundancy, DSM, SINR, Optimization, ETRI]
---
## Project Overview: UAM Communication Redundancy and Scenario Analysis
This project focused on developing a highly precise simulator and optimization methodology for UAM/UTM communication, utilizing real-world geospatial data to ensure reliable connectivity in complex urban and non-terrestrial environments.

### 🛠️ Technical Implementation & Simulator Design

#### 1. Performance Analysis Engine Design (Downlink / Uplink)
* **Precision Modeling:** Designed a performance analysis engine that precisely calculates path loss, interference, and shadowing between the base station and UAV.
* **Real-Environment Reflection:** Incorporated **1m resolution DSM (Digital Surface Model)** data to accurately reflect the real environment.

#### 2. Communication Optimization & Redundancy Analysis
* **Redundancy Structure:** Analyzed redundancy candidate communication technologies (Uplink/Downlink) and base station deployment structures.
* **Multi-Band Analysis:** Derived performance improvement areas by analyzing the propagation characteristics and shadowing/interference patterns across multiple bands (e.g., 433 MHz, 1.8 GHz, 5 GHz).

#### 3. Automated Analysis Pipeline
* **Automation Design:** Designed an automated structure for calculating and analyzing communication metrics.
* **Metrics:** Built a processing pipeline that automatically computes SINR, Coverage, Outage rates, and base station handover events for large sets of coordinate and altitude samples.

---

### 💡 Strategic Optimization Scope (Optimization & Scenario Modeling)

#### 1. Communication/Sensor Performance Simulator Design
* **Quantitative Verification Environment:** Established a quantitative verification environment by modeling parameters such as signal strength, detection probability, and line-of-sight status based on changes in UAM flight altitude, speed, and path.

#### 2. Signal Processing-based Performance Improvement
* **Algorithm Application Structure:** Designed the application structure for performance improvement algorithms, accurately predicting signal quality by reflecting real-environment factors (path loss, reflection, refraction, interference).

#### 3. Comprehensive Scenario-based Simulator Development
* **Implementation:** Implemented a comprehensive simulation algorithm to confirm the stability and continuity of communication links in diverse mission environments (urban, mountainous, coastal, low-altitude), based on various UAM operational scenarios.
