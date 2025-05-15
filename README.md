# room8-deployments
room8 cd deployments with argo cd

## Project structure
```
room8-deployments/
├── apps/
│   ├── service-registry.yaml
│   ├── user-service.yaml
│   ├── auth-service.yaml
│   ├── api-gateway.yaml
├── base/
│   ├── service-registry/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── api-gateway/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   │   ├── ingress.yaml  <-- This is the public entrypoint
│   ├── user-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── auth-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── listings-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── bidding-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── contact-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── feedback-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── search-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── notification-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml

```
