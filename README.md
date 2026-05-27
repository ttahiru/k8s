# Kubernetes CKA Study & Homelab Projects

This repository contains hands-on Kubernetes projects and infrastructure configurations completed while studying for the Certified Kubernetes Administrator (CKA) exam.

---

## Project 1: Production-Grade Kubernetes Cluster Bootstrapping

This project documents the deployment of a two-node Kubernetes cluster on Ubuntu 26.04 LTS using Kubeadm, Containerd, and Calico for high-performance CNI networking. The architecture consists of a dedicated control plane and a worker node, each provisioned with 4GB RAM and hardened via kernel module configuration, swap management, and the verification of unique hardware identifiers (MAC/UUID) to ensure cluster stability. By implementing industry-standard CRI configurations and TLS bootstrapping, this project establishes a scalable, production-ready foundation for hosting containerized microservices in a professional homelab environment.

