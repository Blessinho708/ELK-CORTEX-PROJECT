SOC Lab Setup with ELK Stack, Filebeat & Cortex (Docker Desktop)
 Project Overview

This project demonstrates the deployment of a small Security Operations Center (SOC) lab using Elasticsearch, Kibana, Filebeat, and Cortex, all containerized with Docker Desktop on Windows (WSL). The lab simulates real-world SOC workflows such as log collection, analysis, visualization, and automated threat enrichment.

Objectives

* Deploy Elasticsearch and Kibana using Docker

* Collect logs using Filebeat

* Integrate Cortex for automated threat analysis

* Simulate real SOC analyst workflows

* Gain hands-on experience with Docker Desktop

Tools & Technologies

* Docker Desktop (Windows + WSL)

* Docker Compose

* Elasticsearch – Log storage and search

* Kibana – Dashboards and visualization

* Filebeat – Log collection and forwarding

* Cortex – Threat intelligence enrichment

Architecture Overview

Filebeat collects logs and forwards them to Elasticsearch. Kibana visualizes the ingested data, while Cortex enriches alerts and indicators. All services run as isolated Docker containers managed by Docker Desktop.


Installation & Setup

1.Installed Docker Desktop with WSL enabled

2.Configured Elasticsearch, Kibana, Filebeat, and Cortex using Docker Compose

3.Started all services using docker compose up -d

4.Verified services via Docker Desktop and web interfaces


Configuration & Integration

* Filebeat configured to collect system logs

* Elasticsearch set as Filebeat output

* Kibana connected to Elasticsearch for visualization

* Cortex integrated for alert enrichment


Results & Observations

* Kibana Dashboard
* Cortex Interface


Challenges & Solutions
Challenge	Solution
High memory usage	Adjusted Docker Desktop resource limits
Elasticsearch connection issues	Fixed container networking
Filebeat ingestion errors	Corrected Filebeat output configuration


Skills & Learning Outcomes

* ELK stack deployment with Filebeat

* Log ingestion and visualization

* Threat enrichment using Cortex

* Docker networking and troubleshooting

* SOC analyst workflow simulation



Conclusion

This project demonstrates a functional SOC lab built with Docker Desktop. The integration of Filebeat, ELK, and Cortex provides hands-on experience with log ingestion, analysis, and automated threat intelligence, closely aligning with real-world SOC environments.



