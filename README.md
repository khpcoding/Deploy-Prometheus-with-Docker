# Installation of Prometheus and Alertmanager with Docker Compose

This repository contains the Docker Compose configuration for deploying Prometheus and Alertmanager on a virtual machine (VM). Prometheus is a robust monitoring system, and Alertmanager handles alerts sent by client applications like Prometheus.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Installation

Follow these steps to set up Prometheus and Alertmanager:

**Clone the repository:**

   ```sh
   git clone https://github.com/khpcoding/Installation-Prometheus-with-Docker.git
   cd Installation-Prometheus-with-Docker
   docker compose up -d 
