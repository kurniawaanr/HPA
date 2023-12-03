# HPA - Kubernetes on Minikube

the ideas to create Horizontal Pod Autoscaling based on CPU utilization with prometheus and grafana to continously monitoring cluster. This project aims to fulfill final assignment, it might be a lot of misconception about everything and it might be not a best practice to do.

used tools :

| Software | Version |
| ------------- | ------------- |
| Ubuntu  | v20.04  |
| Minikube  | v1.31.2  |
| Kubernetes  | v1.27.4  |
| Kubectl  | v1.28.4  |
| Docker  | v24.0.4 |
| kube-stats-metrics  | v2.10.0  |
| Prometheus  | v2.47.2  |
| Grafana  | v10.2.0  |

> [!TIP]
> please use specific version mentioned above to avoid error

## Installation Steps
1. install [minikube](https://minikube.sigs.k8s.io/docs/start/)
2. install [kubectl](https://kubernetes.io/docs/tasks/tools/)
3. install [Docker](https://docs.docker.com/engine/install/)


## Deployment Steps
1. deploy demo app (using php-apache) [in this section](https://github.com/kurniawaanr/HPA/tree/main/deployment/php-apache)
2. deploy load generator (using busybox) [in this section](https://github.com/kurniawaanr/HPA/tree/main/deployment/loadtest)
3. deploy Horizontal Pod Autoscaler [in this section](https://github.com/kurniawaanr/HPA/tree/main/autoscaler)
4. deploy configure monitoring tools [in this section](https://github.com/kurniawaanr/HPA/tree/main/deployment/monitoring)
5. deploy [Prometheus](https://github.com/kurniawaanr/HPA/tree/main/deployment/monitoring/prometheus)
6. deploy [Grafana](https://github.com/kurniawaanr/HPA/tree/main/deployment/monitoring/grafana)