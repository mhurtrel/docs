---
title: Available and planned features
excerpt: ''
slug: available-upcoming-features
section: Technical resources
---

**Last updated August 10, 2020.**

We list here the most frequently requested OVHcloud Managed Kubernetes features that are currently available or planned in the upcoming year.

### Available features

- **Persistent Volumes ** Use the integrated Cinder Volumes to host the persistent data of your stateful containerized workloads. Details in the[working with persistent volumes ](../ovh-kubernetes-persistent-volumes/) guide.
- **Load Balancer** Use the integrated External Load balancers to expose your services on any port of a dedicated public IPv4. Details available in the [exposing your services](../using-lb/) guide.
- **Pod autoscaling** Use the  [standard horizontal pod autoscaler](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/){.external} to distribute dynamically your containerized workloads on a given set of worker nodes.
- **Node pools management and CRD** Use the  [NodePools](https://docs.ovh.com/gb/en/kubernetes/node-pools-crd/) to size and resize your cluster dynamically, either through our UI or by editing a CRD though your usual kubernetes tooling.
- **RBAC** Use the standard [RBAC authorization](https://kubernetes.io/docs/reference/access-authn-authz/rbac/){.external} mode to distribute rights within your organization and/or assure compatibility with specific applications.
- **New versions** : We support upcoming versions, during the quarter following their official release. We also propose managed version upgrades.
- **Localisation choice** : We offer you the possibility to choose one of multiple OVH Public Cloud datacenters at cluster creation. We currently propose the service in France (GRA and SBG) and Canada (BHS). During 2020 we will add other OVH Public Cloud datacenters at cluster creation.

### Planned features

- **vRack** : Currently, all traffic between you nodes is encrypted but transit through OVH public network. We will offer private clusters in OVH private network (vRack) later in the year.
- **Nodepools autoscaling** : Additionnaly to pod autoscaling, we will provide you the concept of node pools, allowing your cluster to grow automatically depending on CPU and RAM usage, between your user-defined limits.
- **Bare metal worker nodes** : We will integrate bare metal (physical machines) servers in the worker nodes choice.

and many more : feel free to open a feature request ticket though our support team.
