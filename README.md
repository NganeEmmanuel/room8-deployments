# room8-deployments
room8 cd deployments with argo cd

## Project structure
```
room8-deployments/
├── apps/
│   ├── user-service.yaml
│   ├── demand-service.yaml
│   ├── eureka.yaml
│   ├── api-gateway.yaml
├── base/
│   ├── user-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── demand-service/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── eureka/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   ├── api-gateway/
│   │   ├── deployment.yaml
│   │   ├── service.yaml
│   │   ├── ingress.yaml  <-- This is your ONLY public entrypoint
```
