# Charts Repository

This repository contains Helm charts for deploying microservices.

## Available Charts

### notification-service-chart
- **Version**: 0.1.0
- **App Version**: 0.1.0
- **Description**: A Helm chart for the notification-service
- **Type**: Application

### order-service-chart
- **Version**: 0.1.0
- **App Version**: 0.1.0
- **Description**: A Helm chart for the order-service
- **Type**: Application

## Repository Structure

```
.
├── index.yaml                              # Helm repository index file
├── notification-service-chart-0.1.0.tgz   # Packaged notification service chart
├── order-service-chart-0.1.0.tgz         # Packaged order service chart
└── README.md                              # This file
```

## Usage

### Adding the Repository

To add this Helm repository to your local Helm installation:

```bash
helm repo add charts https://erickk0.github.io/charts
helm repo update
```

### Installing Charts

To install a chart from this repository:

```bash
# Install notification service
helm install notification-service charts/notification-service-chart

# Install order service
helm install order-service charts/order-service-chart
```

### Viewing Available Charts

To list all available charts in this repository:

```bash
helm search repo charts
```

## Repository Information

- **Repository URL**: https://erickk0.github.io/charts
- **Generated**: 2025-10-03T23:52:17.902439+02:00
- **API Version**: v1

## Chart Maintenance

This repository contains packaged Helm charts (.tgz files) and the corresponding index.yaml file that serves as the repository index for Helm.