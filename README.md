a project to deploy a kubernetes cluster to GCP 

# GKE DEPLOY
An unnecesary complex app using Kubernetes to showcase how to deploy a kubernetes managed app in Google Kubernetes Engine.
# Services:
- Client: A React App consuming an API to show fibonacci numbers.
- Server: The API to be consumed, made with Express.
- Worker: A service which calculates the value of the fibonacci number required, using a Redis instance in the AWS VPC Used, made with Express.
- Nginx-ingress: Ingress for routing the request to the appropiate service, setting up HTTPS,etc.
