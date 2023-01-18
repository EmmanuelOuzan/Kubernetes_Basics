
***Hello Everyone
This is my first kubernetes project
Creation of :
Pods, Services & Deployments.
I have created an app composed of 5 pods.
This is a voting app. 
You should vote if you prefer dogs or cat, and it should output the result.
Pods that have been deployed:
1. voting-app
2. Redis
3. .Net
4. Postgres
5. Result-app

Services created:
redis-service : ClusterIP (To talk with the cluster)
Postgres-service : ClusterIP
Two NodePorts:
1. for accesing the Voting-app on port 80
2. for accesing the results-app on port 80
