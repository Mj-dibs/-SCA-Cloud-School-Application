# -SCA-Cloud-School-Application
 
 This repository is an example of a containerized node.js application using Docker.

## Instructions

* Install Docker on your local machine and confirm that it is running.
* Create a docker hub account if you do not have one already.
* Clone Github repo containing the app
	git clone https://github.com/Mj-dibs/SCA-Cloud-School-Appplication.git
* Create a Dockerfile.
* Build the image 
	docker build -t mjdibs/sca-cloud-school-appplication .
* Run the image's default command. The -p option forwards the container's port to an appropriate port of your choosing on the host.
	 docker run -p 8888:3000 mjdibs/sca-cloud-school-appplication
* Once successful the webapp can be accessed via http://localhost:8888
* Log in to Dockerhub and push the final image to your docker repo.
	docker push mjdibs/sca-cloud-school-appplication

### Link Example
 [Dockerhub repo](https://hub.docker.com/repository/docker/mjdibs/sca-cloud-school-appplication)
 
