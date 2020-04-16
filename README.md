# ServiceMesh TLS with Cert-Manager
This example demonstrates how to use cert-manager with ServiceMesh for tls ingress gateways.

## Configuration
1. Update values.yaml for your environment
1. Update the hosts to reflect the dns host that will be created in the route
1. Update the issuer name and type to match your cert-manager environment

## Deploy
```
helm install tls-ingress .
```