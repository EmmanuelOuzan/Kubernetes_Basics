# Kubernetes Deplyoment of a voting app 
## Vote for cats or dogs with a full kubernetes app from scratch.
### Creation of : Pods, Services & Deployments

I have created an app composed of 5 pods.

You should vote if you prefer dogs or cat, and it should output the result.

Pods that have been deployed:
1. voting-app
2. Redis
3. .Net
4. Postgres
5. Result-app

Services created:
redis-service : ClusterIP 
(To communicate with the cluster)
Postgres-service : ClusterIP
Two LoadBalancer:
1. Accesing the Voting-app on port 80
2. Accesing the results-app on port 80

![image](https://user-images.githubusercontent.com/8169459/213927201-4f886890-9c09-4137-9f5f-0390528918f0.png)
