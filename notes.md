
## advantages

- canary tests
  - select a small group of people to run a test 
- redundancy
- distribute load among infrastructure
- autoscale based on custom factors
- uses master - agent roles to distribute jobs (master assigns agents to run/deploy)
- k8s config files that describe automated processes
- orchestrate compute, network and storage resources
- self healing apps based on custom parameters
- secret and configuration management
- green/blue deployment strategy
  - these are what we know as rolling updates
- high availability

running k8s cluster contains node agents (kubelet) and a cluster control plane (master) with cluster state backed distributed configuration (etcfs)

## control plane
- set of components which can run in a single master node or can be replicated in order to support the cluster
- keeps a record  

## k8s object
can refer to a node, service, replica set, pod, not a namespace or config, an entity

## 




