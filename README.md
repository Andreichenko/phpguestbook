### Stateless application (GKE)
We have a deployment of Frontend, Redis master, Redis slave, two ClusterIP services and LoadBalancer service.

Some steps:
1. Create a standard 3 node GKE cluster
2. Use all default settings
3. Authenticate kubectl with cloud:
```sh gcloud container clusters get-credentials <our-cluster-name> --zone=<zone> ```


![gke drawio](https://user-images.githubusercontent.com/20015341/140773479-51bea6f8-bfee-4216-bcc7-17960ce2ef56.png)
