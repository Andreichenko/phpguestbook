### Stateless application (GKE)
We have a deployment of Frontend, Redis master, Redis slave, two ClusterIP services and LoadBalancer service.

Some steps:
1. Create a standard 3 node GKE cluster
2. Use all default settings
3. Authenticate kubectl with cloud:
```sh gcloud container clusters get-credentials <our-cluster-name> --zone=<zone> ```


![gke drawio-2](https://user-images.githubusercontent.com/20015341/140773908-684ba5a7-deab-40c5-b628-95afc3a1bb07.png)
