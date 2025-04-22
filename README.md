# k8-deployment

A collection of Kubernetes deployment configurations for various applications and services.

## Contents

This repository includes the following configuration files:

- `config.yaml`: Deploys Kubernetes clusters using predefined specifications.
- `countdown.yml`: Deployment configuration for a countdown application.
- `glowboard.yml`: Deployment configuration for the Glowboard application.

## Usage

To deploy any of the configurations:

1. Ensure you have access to a Kubernetes cluster and that `kubectl` is configured.
2. Apply the desired configuration file using:

   ```bash
   kubectl apply -f <filename>.yaml
