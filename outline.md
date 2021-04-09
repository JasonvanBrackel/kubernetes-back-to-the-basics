# Kubernetes Back to the Basics - Pods

## What is a Pod

- Abstraction 
- Smallest Atomic Unit of Deployment and Scale
- Set off Linux constructs
  - namespaces
  - cgroups
  - other isolation mechanisms
    - files system volumes

- Don't usually create a Pod, Created by other Workloads
  - Deployment
  - Jobs
  - Stateful Sets

- What do Pods do for containers
  - Shared Namespaces
  - Shared Filesystem
  - Survivability

- How do they do that?
  - The Pause Container
  

## For More Information

[Kubernetes Documentation / Concepts / Workloads / Pods](https://kubernetes.io/docs/concepts/workloads/pods/)