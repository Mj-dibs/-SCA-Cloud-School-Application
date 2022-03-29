# -SCA-Cloud-School-Application
 
 This repository is an example of a containerized node.js application using Docker.

## Instructions

* Install Docker on your local machine and confirm that it is running.
* Create a docker hub account if you do not have one already.
* Clone Github repo containing the app you wish to dockerize.
* Create a Dockerfile.
* Build the image 
	docker build -t="my-app" docker-sample
* Run the image's default command. The -p option forwards the container's port to an appropriate port of your choosing on the host.
	 docker run -p="8000:80" my-app
* Once successful the webapp can be accessed via http://localhost:(your port)/ on your host machine.
* Log in to Dockerhub and push the final image to your docker repo.

### Link Example
 [Dockerhub repo](https://hub.docker.com/repository/docker/mjdibs/sca-cloud-school-appplication)
 
