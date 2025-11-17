AWS EC2 Monitoring Using Prometheus, Node Exporter & Grafana
📌 Project Overview

This project sets up a complete monitoring stack on an AWS EC2 Ubuntu instance using:
- Prometheus for metric collection
- Node Exporter for system-level metrics
- Grafana for dashboards and visualization

It demonstrates how to monitor CPU, memory, disk, network, and general server health in real time.

🛠️ Setup Steps
1. Install Prometheus
- Download latest release
- Extract binaries
- Configure storage paths
- Create systemd service
- Enable and start Prometheus on port 9090
2. Install Node Exporter
- Download Node Exporter
- Setup as a systemd service
- Metrics available on port 9100

3. Configure Prometheus Scrape Targets

Prometheus scrapes:
- Target	Port
- Prometheus	9090
- Node Exporter	9100
4. Install Grafana

- Add Grafana APT repo
- Install package
- Enable Grafana service
- Access via http://<EC2-Public-IP>:3000

5. Import Dashboards
- Imported EC2 / Linux dashboards to visualize:
- CPU Utilization
- Memory Usage
- Load Average
- Disk I/O
- Network traffic
- Running processes

📸 Screenshots
1️⃣ EC2 Instance
<img width="1919" height="875" alt="EC2" src="https://github.com/user-attachments/assets/55f68ac1-5e7f-4a4a-97c7-33aea09b2f43" />
2️⃣ Prometheus UI
<img width="1919" height="1019" alt="Prometheus UI" src="https://github.com/user-attachments/assets/db22db6b-762c-462c-a948-1267d010dc2f" />
3️⃣ Prometheus Targets
<img width="1919" height="1010" alt="Prometheus Targets" src="https://github.com/user-attachments/assets/bc521de3-9f56-407f-b642-8c5aed5b5be0" />
4️⃣ Prometheus Query
<img width="1919" height="1023" alt="Prometheus Query" src="https://github.com/user-attachments/assets/e696d49a-f6c1-48d4-ae45-5120c2edd029" />
5️⃣ Node Exporter Metrics
<img width="1919" height="1023" alt="Node Exporter" src="https://github.com/user-attachments/assets/74bb7f8b-c4c5-4d68-a8cc-bfbc70bc1dfa" />
6️⃣ prometheus.yml
<img width="1919" height="886" alt="Prometheus config" src="https://github.com/user-attachments/assets/a9f71353-72b6-42c7-816a-ce908c33a692" />
7️⃣ Grafana Dashboard
<img width="1919" height="1014" alt="Grafana Dashboard" src="https://github.com/user-attachments/assets/e566563c-db8e-43fa-b5f9-de921d1c2817" />

Tech Stack:
- AWS EC2 (Ubuntu 24.04)
- Prometheus
- Node Exporter
- Grafana
- Systemd services
- Linux administration

What I Learned:
- Setting up a real monitoring stack
- Configuring scrape jobs
- Creating systemd services
- Working with dashboards
- Understanding observability basics

👤 Author
Mohd Ayoub
🔗 LinkedIn: https://www.linkedin.com/in/ermohdayoub/
🐙 GitHub: https://github.com/ermohdayoub
