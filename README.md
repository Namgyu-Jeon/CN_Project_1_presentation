# 🚀 Technical Analysis and Response for Latency-Critical Networks to Advance Autonomous Driving

[cite_start]Welcome to the project repository for evaluating and designing Latency-Critical Networks (LCN) for next-generation autonomous vehicles[cite: 2]. [cite_start]This research focuses on ensuring deterministic network performance within highly non-deterministic wireless environments[cite: 29, 30].

## 👥 Project Overview
* **Course:** Computer Networks
* [cite_start]**Team Members:** Namgyu Jeon, Yegyu Jeon, Seungchan Jo, Seokho Jo [cite: 1]
* [cite_start]**Objective:** To formulate an End-to-End (E2E) latency analysis model [cite: 44] [cite_start]and verify network performance (latency, jitter, packet loss) using NS-3 simulations for autonomous driving scenarios[cite: 45].

## 🎯 My Contributions: Wireless Protocol & URLLC Analysis
[cite_start]As the lead for the wireless network segment, my core responsibilities include[cite: 59]:
* [cite_start]**3GPP 5G/6G URLLC Analysis:** Investigating physical layer technologies (e.g., mini-slots, grant-free access) to guarantee sub-millisecond latency[cite: 39, 59, 82].
* [cite_start]**Latency Optimization:** Identifying latency factors within the wireless segment and establishing strategies to mitigate them[cite: 59].
* [cite_start]**Network Slicing Application:** Researching 5G network slicing techniques to logically separate critical control traffic from best-effort data[cite: 59].

## 🏗️ Integrated LCN Architecture
Our research integrates multiple networking domains to guarantee strict time constraints:
1. [cite_start]**L2 In-Vehicle Wired TSN:** Utilizing IEEE 802.1Qbv (Time-Aware Shaper) to eliminate collisions for critical control data[cite: 66, 67].
2. [cite_start]**Wireless 5G URLLC:** Bridging TSN with 5G systems via DS-TT/NW-TT and utilizing IEEE 802.1AS for precise microsecond time synchronization[cite: 39, 73, 74].
3. [cite_start]**MEC (Multi-access Edge Computing):** Processing data at the network edge to drastically reduce Round-Trip Time (RTT)[cite: 19].
4. [cite_start]**L3 Wide-Area DetNet:** Applying IETF DetNet with Packet Replication and Elimination Function (PREOF) to ensure reliability across multi-hop router networks[cite: 78, 79].

## 📊 Expected Deliverables
* [cite_start]Integrated End-to-End Latency Model [cite: 44]
* [cite_start]NS-3 Simulation Data (Platooning scenarios) [cite: 45]
* [cite_start]Industry standard-based technical guidelines for autonomous driving [cite: 46]

*👉 [Interactive Presentation Dashboard](https://namgyu-jeon.github.io/CN_Project_1_presentation/)*
