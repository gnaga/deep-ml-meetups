# All-in-one Docker image for Deep Learning and Bayesian Machine Learning

Image based on:
https://github.com/floydhub/dl-docker

(Work In progress) 
https://hub.docker.com/r/quantscientist/www.deep-ml.com/ 

![Building the image](nice-docker.png)

# Image contents
On top of all the fancy deep learning libraries, this docker image contains:

* PyStan
* PyMC3
* Edward
* FB Prophet

# Get the image

docker pull quantscientist/deep-bayes

# Build the image

docker build -t docker pull quantscientist/deep-bayes -f Dockerfile.cpu .

See https://github.com/docker/dceu_tutorials/blob/master/08-Automated-builds.md
