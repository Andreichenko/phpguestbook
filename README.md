*** Stateless application (GKE)
We have a deployment of Frontend, Redis master, Redis slave, two ClusterIP services and LoadBalancer service.

Some steps:
1. Create a standard 3 node GKE cluster
2. Use all default settings
3. Authenticate kubectl with cloud:
``` gcloud container clusters get-credentials <our-cluster-name> --zone=<zone> ```
 