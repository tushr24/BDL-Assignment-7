# BDL Assignment 7

# Health Monitoring of FastAPI

## Overview
FastAPI Health Monitoring through Prometheus web scraping for metrics and Grafana for visualization of the metrics. 

## Installation
Install Docker and WSL to your local computer.

Run the command `docker-compose up --build` to start the FastAPI application and host the Grafana UI

## Walkthrough of Code

* The main.py file contains the following metrics posted to Prometheus
    1. API Usage Counters: Number of hits from different client IP addresses.
    2. API Run Time: Total time taken by the API to process requests.
    3. API Processing Time (T/L): Effective processing time per character.
    4. CPU Utilization: Rate of CPU usage by the FastAPI application.
    5. Memory Utilization: Memory used by the FastAPI application.
    6. Network I/O: Bytes sent and received by the application.
    7. Network I/O Rate: Rate of bytes sent and received by the application 

    These can be queried in Grafana and visualized
