### Example Voting App by Docker Hub

This is based on the original [example-voting-app](https://github.com/dockersamples/example-voting-app) from docker-examples(https://github.com/dockersamples) modified to work on Kubernetes   



Execute following commands on Any Kubernetes cluster available in Public Cloud (like Azure, AWS or GCP etc,). Reason for Public Cloud is we have two services of type Load Balancer, which can't be used on local setup.


Kubernetes Services : Type   
db  : ClusterIP      
redis   : ClusterIP    
result-service  :  LoadBalancer    
voting-service   :  LoadBalancer    

```
kubectl create -f .
```
