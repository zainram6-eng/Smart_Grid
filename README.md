# Smart_Grid
Full-stack client-server system for real-time smart grid data ingestion, relational storage (PostgreSQL), and automated load rebalancing.


##  Key Features

* **Real-Time Data Ingestion:** Multi-threaded client-server architecture built to handle concurrent measurement streams from distributed grid sensors.
* **Scalable Storage Backend:** Designed and implemented a robust PostgreSQL database schema optimized for efficient timeseries data logging and large-scale retrieval.
* **Automated Grid Rebalancing:** Developed algorithmic grid-stabilization logic to detect anomalies, balance loads, and automate grid routing decisions.
* **Object-Oriented Design:** Clean, modular code separation using Java and Python to ensure system scalability and ease of maintenance.

##  Tech Stack

* **Languages:** Python, Java
* **Database:** PostgreSQL
* **Architecture:** Client-Server, Distributed Systems, Object-Oriented Programming (OOP)
* **Core Concepts:** Real-time data streaming, Threading, Grid optimization algorithms

##  System Architecture

1. **Sensor Simulation Layer (Client):** Generates and transmits simulated grid metrics (voltage, current, load) at regular intervals.
2. **Central Monitoring Server:** Receives incoming streams, parses data payloads, and handles concurrent client connections safely.
3. **Database Layer:** Persists structural and timeseries sensor data into optimized PostgreSQL tables.
4. **Decision Engine:** Evaluates metrics against dynamic thresholds to trigger grid rebalancing operations when necessary.
