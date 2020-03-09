# ML-deployment-with-flask-docker-kubernetes
Deploying a Random forests model using flask/docker/kubernetes


Use the train-rand-for.ipynb notebook to train a random forest model.
install the required python libraries using pip
store this model as a pkl file in the docker-flaskapp folder



Use docker for widows/mac to create an image using the pkl file ansd flask app provided in the docker-flaskapp folder
use the dockerfile in docker-flaskapp folder to create the docker image
Run this image to create a running cotainer. This container can be accessed using local host and the port you assign the container


Once the container is running it can be infered using infer-model.ipynb notebook


use the test3.yaml file to deploy to kubernetes or minikube as a deployment of 5 replicas
