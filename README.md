AWS EC2 Monitoring Using Prometheus, Node Exporter & Grafana

This project demonstrates a complete monitoring stack deployment on an AWS EC2 Ubuntu instance using Prometheus, Node Exporter, and Grafana.

  Setup Overview
1. Install Prometheus

Download latest Prometheus release

Extract and copy binaries

Configure storage directory structure

Setup as a systemd service

2. Install Node Exporter

Download and run Node Exporter service

Exposes system metrics on port 9100

3. Configure Prometheus Scrape Targets

Prometheus scrapes:

Itself (:9090)

Node Exporter (:9100)

4. Install Grafana

Add Grafana APT repo

Install and enable Grafana service

Login on :3000 and add Prometheus as data source

5. Import Dashboards

Imported Linux/EC2 dashboards to visualize:

CPU usage

Memory usage

Disk IO

Load average

Network throughput

📸 Screenshots
1️⃣ EC2 Instance
<img width="1919" height="875" alt="Screenshot 2025-11-17 194213" src="https://github.com/user-attachments/assets/55f68ac1-5e7f-4a4a-97c7-33aea09b2f43" />

2️⃣ Prometheus UI


<img width="1919" height="1019" alt="Screenshot 2025-11-17 200200" src="https://github.com/user-attachments/assets/db22db6b-762c-462c-a948-1267d010dc2f" />


3️⃣ Prometheus Targets (All UP)


<img width="1919" height="1010" alt="Screenshot 2025-11-17 194313" src="https://github.com/user-attachments/assets/bc521de3-9f56-407f-b642-8c5aed5b5be0" />

4️⃣ Prometheus Metrics Query

<img width="1919" height="1023" alt="Screenshot 2025-11-17 194430" src="https://github.com/user-attachments/assets/e696d49a-f6c1-48d4-ae45-5120c2edd029" />


5️⃣ Node Exporter Metrics Page


<img width="1919" height="1023" alt="Screenshot 2025-11-17 194454" src="https://github.com/user-attachments/assets/74bb7f8b-c4c5-4d68-a8cc-bfbc70bc1dfa" />

6️⃣ prometheus.yml Configuration

<img wid<img width="1919" height="886" alt="Screenshot 2025-11-17 194949" src="https://github.com/user-attachments/assets/a9f71353-72b6-42c7-816a-ce908c33a692" />



7️⃣ Grafana Dashboard (EC2 Monitoring)
<img width="1919" height="1014" alt="Screenshot 2025-11-17 195128" src="https://github.com/user-attachments/assets/e566563c-db8e-43fa-b5f9-de921d1c2817" />


🧰 Technologies Used

AWS EC2

Prometheus

Node Exporter

Grafana

Ubuntu Linux

Systemd Services

📚 Purpose

This project is a hands-on practice to demonstrate:

Monitoring setup

Metric collection

Visualization dashboards

Linux and system services

DevOps observability tools

📬 Author

Mohd Ayoub
LinkedIn: https://www.linkedin.com/in/ermohdayoub/
GitHub: ermohdayoub
