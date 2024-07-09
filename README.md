# Prometheus and Grafana Monitoring Setup
To set up a monitoring solution for your local server using Prometheus and Grafana, here we have all within one Docker Compose:

****Prerequisites****
Ensure Docker and Docker Compose are installed on your local machine.

****Step-by-Step Guide****

Create a Docker Compose file (.yml) that contains both Grafana and Prometheus images.

Link Prometheus to your session server Prometheus endpoint.

Configure your Grafana data source to communicate with Prometheus and import the pre-configured dashboards.

Configure the Grafana dashboards

Access Grafana.

**Instructions:**
1. Clone the repository:

   ```sh
   git clone https://github.com/SumairaS/Docker-Compose-Prometheus-Grafana
   cd prometheus-grafana
 2.  Run Docker Compose:
     ```sh
     docker-compose up -d
     
 3. Check if it's up and running:


**Accessing the Services**

Prometheus: http://localhost:9090



Grafana: http://localhost:3000

**Default Grafana login:**

Username: admin

      

Password: admin

4. To Stop all the services:
   ```sh
    docker-compose down

   
