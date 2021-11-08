### Stateless application (GKE)
We have a deployment of Frontend, Redis master, Redis slave, two ClusterIP services and LoadBalancer service.

Some steps:
1. Create a standard 3 node GKE cluster
2. Use all default settings
3. Authenticate kubectl with cloud:
```sh gcloud container clusters get-credentials <our-cluster-name> --zone=<zone> ```

![gke3 drawio](https://user-images.githubusercontent.com/20015341/140774521-d483b61d-35a7-4850-8073-58c67bf5a247.png)
