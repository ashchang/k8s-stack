# k8s-stack

### CDK: 

- EKS: > AddOns: VPC-CNI, Kube-Proxy, Core-DNS
- Karpenter: https://karpenter.sh/docs/
- aws-loadbalance-controller: https://artifacthub.io/packages/helm/aws/aws-load-balancer-controller

### Manual:
Can be installed by Helm

#### Ingress & Gateways
need to be installed in every cluster

- Istio: https://artifacthub.io/packages/helm/istio-official/istiod

(only use **istiobase, istio-ingress-gateway, istiod, istio-operator**)

#### CICD Related

- DroneCI: https://artifacthub.io/packages/helm/community-charts/drone

- argocd: https://artifacthub.io/packages/helm/argo/argo-cd
- argocd-apps: https://artifacthub.io/packages/helm/argo/argocd-apps
- argocd-image-updater: https://artifacthub.io/packages/helm/argo/argocd-image-updater

#### Tracing
- jaegertracing: https://artifacthub.io/packages/helm/jaegertracing/jaeger

#### Monitoring
- Prom: https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack
- Gatus: https://artifacthub.io/packages/helm/minicloudlabs/gatus
- Metric-server: https://artifacthub.io/packages/helm/metrics-server/metrics-server

#### Logs
- Fluentd-Elasticsearch: https://artifacthub.io/packages/helm/kokuwa/fluentd-elasticsearch
- Elasticsearch: https://artifacthub.io/packages/helm/elastic/elasticsearch
- Kibana: https://artifacthub.io/packages/helm/elastic/kibana


---

Some tools that you might want to use:

- k9s: https://k9scli.io/
- k3d: https://k3d.io/v5.5.1/
- eks-node-viewer: https://github.com/awslabs/eks-node-viewer
