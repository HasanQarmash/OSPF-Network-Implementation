<p align="center">
  <img src="https://user-images.githubusercontent.com/102525495/2c8c49e5-6b6f-474c-83b6-20d2d3a0429a.png" width="800" alt="Network Topology Banner"/>
</p>

<h1 align="center">OSPF Network Implementation with Cisco Packet Tracer</h1>

<p align="center">
  A comprehensive university project demonstrating a multi-area OSPF network with fully configured services.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tech-Cisco_Packet_Tracer-00AEFF?style=for-the-badge&logo=cisco" alt="Cisco Packet Tracer Badge"/>
  <img src="https://img.shields.io/badge/Protocol-OSPF-FF6600?style=for-the-badge" alt="OSPF Badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" alt="Status Badge"/>
</p>

---

## 🚀 Overview

Welcome to the **OSPF Network Implementation** project! This repository showcases a simulated enterprise network, meticulously designed and configured in **Cisco Packet Tracer**. The project serves as a practical application of core computer networking principles, moving from theoretical concepts to a fully functional, multi-area network.

The core of this project is the strategic implementation of the **Open Shortest Path First (OSPF)** routing protocol to ensure efficient and reliable communication across various network segments, including a data center and multiple corporate offices.

## ✨ Key Features

-   **🧠 Intelligent Subnetting:** The IP addressing scheme is logically derived from a student ID, showcasing a systematic approach to network subnetting and address allocation.
-   **🌐 Multi-Area OSPF Configuration:** The network is segmented into multiple OSPF areas to demonstrate a hierarchical and scalable routing design.
    -   **Area 0:** The core backbone connecting all other areas.
    -   **Area 1:** Data Center network.
    -   **Area 2 & 3:** Company A and Company B networks.
    -   **Area 4:** Company C's branch offices.
-   **🔧 Full Service Deployment:** Configuration of essential network services to simulate a real-world environment.
    -   **DNS Server:** Resolving `www.FirstSem2024.com`.
    -   **Web (HTTP) Server:** Hosting a custom project website.
    -   **Email Server:** Managing user accounts with SMTP/POP3 services.
-   **💻 End-to-End Connectivity:** Static IP configuration for all end devices (PCs and Servers) and thorough validation of network-wide communication.

## 📊 Network Architecture

The topology was designed to represent a realistic corporate structure, featuring a central data center and distinct company networks, all interconnected through a core router backbone.

| Network Segment       | OSPF Area | # of Devices | Network IP          |
| --------------------- | :-------: | :----------: | ------------------- |
| **Data Center**       |     1     |      5       | `200.3.10.96/28`    |
| **Company A**         |     2     |      26      | `200.3.10.0/27`     |
| **Company B**         |     3     |      24      | `200.3.10.32/27`    |
| **Company C Office 1**|     4     |      10      | `200.3.10.64/28`    |
| **Company C Office 2**|     4     |      14      | `200.3.10.80/28`    |
| **Core Router Links** |     0     |      -       | Point-to-Point Links|

## 🛠️ Getting Started

To explore this simulation, you'll need **Cisco Packet Tracer** installed.

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/OSPF-Network-Implementation.git
    ```

2.  **Launch the Simulation**
    -   Navigate to the cloned directory.
    -   Open the **`.pkt`** file. The complete topology and all device configurations are saved within this file.

3.  **Explore the Documentation**
    -   The `Computer_Networks_Second_Project.pdf` provides a detailed, step-by-step report of the project, including configuration commands, verification snapshots, and analysis of test results.

## 🔬 Testing & Verification

The network's functionality was rigorously tested to ensure flawless connectivity and service accessibility.

*   **Connectivity (`ping`):** Every PC can successfully ping every other PC in the network, regardless of its subnet.
*   **Path Tracing (`tracert`):** The routes between devices were traced to verify that OSPF was directing traffic along the optimal paths.
*   **Web Access:** All PCs can successfully access `http://www.FirstSem2024.com`, confirming that DNS and HTTP services are correctly configured.


## 👥 Project Team

This project was a collaborative effort by:

-   **Hasan Qarmash** (`1210611`)
-   **Ahmad Hussin** (`1210326`)
-   **Abdallah audah** (`1210571`)

### Under the Supervision of:

-   Dr. Abdalkarim Awad
-   Dr. Imad Tartir

---

<p align="center">
  A project for the Department of Electrical and Computer Engineering at <strong>Birzeit University</strong>.
</p>
