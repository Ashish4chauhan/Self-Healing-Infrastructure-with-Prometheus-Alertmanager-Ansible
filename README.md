Self-Healing Infrastructure with Prometheus, Alertmanager & Ansible

Introduction

In modern cloud-native environments, ensuring high availability and resilience is critical. Automation plays a key role in minimizing downtime and improving system reliability.
This project demonstrates how to implement a self-healing infrastructure using Prometheus for monitoring, Alertmanager for alerting, and Ansible for automated remediation.
An Ubuntu-based EC2 instance hosts an NGINX web service, which is continuously monitored. If the NGINX service fails, the system automatically detects and restarts it through an Ansible playbook — achieving a fully automated recovery process.
