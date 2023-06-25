# Deploying a Nodejs application using docker 
- a node js app was gotten 
- docker images required to run  the app like mongodb and mongo express were gotten from dockerhub
- both images were built/run and containers were created..
- both containers were connected to a single network using the mongo.yaml file
- a my-app:1.0 container was created and attached to the existing network..this was done to merge all the containers into one and form a single network
- an AWS Elastic Cloud Repository [ECR] was created and connected to the host machine  
- a NEW  image was created using Dockerfile ,,that image would be saved on an AWS ECR docker REPOSITORY earlier created..
- we confirmed that our app was working properly by combining all the configured containers and ran them as a script in  a docker-compose.yaml file
