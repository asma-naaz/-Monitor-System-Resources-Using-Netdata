# TASK-7

# -Monitor-System-Resources-Using-Netdata

# Overview
This project sets up Netdata using Docker to monitor real-time system resources, including CPU, memory, disk, and Docker containers. Netdata is a powerful, open-source, and distributed real-time monitoring tool that provides visual insights into system performance and alerts for critical resource thresholds. This project helps track and monitor the health of a system, ensuring better performance and quicker issue detection.

# Objective
* Install Netdata using Docker.
* Monitor real-time system metrics, including CPU, memory, disk usage, network traffic, and Docker containers.
* Configure alerts to notify if resource thresholds exceed predefined limits.
* Explore system logs to troubleshoot and analyze system behavior.

# Tools Used
Netdata: Real-time monitoring tool to visualize system and application metrics.
Docker: Containerization platform used to deploy the Netdata agent easily.

# Prerequisites
* Docker must be installed on your system. 

* Steps to Run Netdata
* Pull Netdata Docker Image: Run the following command to pull the official Netdata Docker image:

![Screenshot 2025-04-17 142341](https://github.com/user-attachments/assets/7e78e486-2798-4059-8257-f864038719e3)

* This will run the Netdata container in detached mode and expose the dashboard on port 19999.

# Access the Dashboard:
* Open your web browser and navigate to:
* http://localhost:19999
* You should see the real-time performance metrics of your system.

![Screenshot 2025-04-17 143016](https://github.com/user-attachments/assets/7fe7dc28-54a8-484b-9b36-462f2b659240)

![Screenshot 2025-04-17 143555](https://github.com/user-attachments/assets/c85bc1da-be49-4340-a154-53b09b9f9fde)

# Monitoring System Resources

* Once the Netdata dashboard is accessible, you can monitor various system metrics:
* CPU Usage: Visualizes the real-time CPU usage of each core.
* Memory Usage: Displays RAM usage, swap space, and memory availability.
* Disk Usage: Tracks disk read/write activity and disk space usage.
* Network Traffic: Monitors incoming and outgoing network traffic.
* Docker Containers: If Docker is running, Netdata will show metrics for running containers.
