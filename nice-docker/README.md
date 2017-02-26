# All-in-one Docker image for Deep Learning and Bayesian Machine Learning

Image based on:
https://github.com/floydhub/dl-docker

(Work In progress) 
https://hub.docker.com/r/quantscientist/www.deep-ml.com/ 


# Image contents
On top of all the fancy deep learning libraries, this docker image contains:

* PyStan
* PyMC3
* Edward
* FB Prophet

# Get the image

docker pull floydhub/dl-docker:cpu

# Build the image

docker build -t quantscientist/bayes-docker:cpu -f Dockerfile.cpu .