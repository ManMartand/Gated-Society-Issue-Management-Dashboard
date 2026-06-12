# Gated Society Issue Management Dashboard

A cloud-hosted issue management dashboard built for a gated society use case. The application allows residents to report common society-level issues and track their status in real time.

This project demonstrates application hosting on AWS EC2, Linux-based deployment, Nginx configuration, Firebase Firestore integration, CRUD functionality, and basic infrastructure monitoring using Prometheus and Grafana.

## Live Demo

This project was deployed and tested on an AWS EC2 instance using Nginx.

> The EC2 instance is currently stopped to avoid AWS charges. It can be started again for live demonstration when required.

Demo URL: http://3.110.114.44

## Use Case

In many gated societies, residents face issues related to maintenance, water supply, parking, security updates, housekeeping, electricity, and general complaints. This dashboard provides a simple way to report, view, update, and track such issues from one place.

The goal of this project was to practice cloud hosting, application support, issue tracking workflow, and monitoring in a realistic operational scenario.

## Features

* Resident issue reporting
* Username-based issue creation
* Real-time issue storage using Firebase Firestore
* Open and resolved status tracking
* Green tick indicator for resolved issues
* Delete issue functionality
* Hosted on AWS EC2
* Served using Nginx
* Linux server deployment and verification
* Infrastructure monitoring using Node Exporter, Prometheus, and Grafana

## Tech Stack

* HTML
* CSS
* JavaScript
* Firebase Firestore
* AWS EC2
* Linux
* Nginx
* Prometheus
* Grafana
* Node Exporter

## Cloud Deployment

The application was deployed on an AWS EC2 instance using a Linux server.

Deployment activities included:

* Launching and connecting to an EC2 instance
* Installing and configuring Nginx
* Hosting static frontend files
* Testing browser access using the EC2 public IP
* Verifying HTTP response using curl
* Checking Nginx access logs for request validation

## Monitoring Setup

A separate EC2 instance was configured as a monitoring server.

Monitoring setup included:

* Node Exporter exposing Linux system metrics on port 9100
* Prometheus scraping metrics from Node Exporter on port 9090
* Grafana visualizing server metrics on port 3000
* Dashboard tracking CPU, memory, disk, network, and uptime metrics

## Verification

The project was verified using the following checks:

* Website access tested through browser
* HTTP response verified using curl
* Nginx access logs checked using `/var/log/nginx/access.log`
* Firebase Firestore tested for issue creation and status updates
* Prometheus target verified as `UP`
* Grafana dashboard configured successfully

## Skills Demonstrated

* AWS EC2 hosting
* Linux server basics
* Nginx configuration
* Firebase Firestore integration
* Frontend development using HTML, CSS, and JavaScript
* Application deployment
* Issue tracking workflow
* Basic infrastructure monitoring
* Troubleshooting and verification
* Documentation for cloud support and application support roles

## Project Summary

This project demonstrates how a simple cloud-hosted application can support a real-world gated society issue management workflow. It combines frontend development, real-time database integration, AWS EC2 hosting, Linux deployment, Nginx configuration, and infrastructure monitoring.

The project is aligned with Cloud Support Engineer, AWS Support Engineer, Cloud Operations Engineer, Application Support Engineer, and Infrastructure Support roles.
