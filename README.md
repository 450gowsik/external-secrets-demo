External Secrets Integration with Kubernetes
Overview

This project demonstrates how to manage secrets securely in Kubernetes using External Secrets Operator (ESO).

Instead of storing credentials directly inside Kubernetes manifests, secrets are fetched from an external provider and automatically synchronized into Kubernetes Secrets.

This implementation uses:

Kubernetes
Helm
External Secrets Operator
SecretStore
Pod Secret Injection
