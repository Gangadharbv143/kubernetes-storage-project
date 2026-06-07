# Kubernetes Storage Project (PV & PVC)

## Overview
This project demonstrates Kubernetes Persistent Volumes (PV) and Persistent Volume Claims (PVC).

## Components
- Persistent Volume (PV)
- Persistent Volume Claim (PVC)
- Pod using persistent storage

## Features
- Persistent data storage
- Data survives pod deletion
- Kubernetes storage management

## Files
- pv.yaml
- pvc.yaml
- pod.yaml

## Verification
Data was written to the volume and remained available after deleting and recreating the pod.

## Technologies
- Kubernetes
- Minikube
- Persistent Volumes
- Persistent Volume Claims
