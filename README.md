# CSC519-TechTalks
### Advanced Docker Usage - Docker Compose [10]
* Install - Docker/ Docker Compose
* Motivation
* Example
	* Instructions
	* Screencast
	* Slides
* Related Concepts
	* Compose + Swarm
	* Compose + Swarm = Kubernetes?
* References


### Setup Instructions [20]
In order see `docker-compose` at work, first need to install docker.

#### Pre-req - Install Docker/ Docker Compose
There are several options to get Docker. One is installing based on the OS from the [docker install page](https://docs.docker.com/engine/installation/#docker-variants). 

Another option is to run a VM that can host docker. The preferred host OS for VM include ubuntu or CoreOS. 
[Docker workshop](https://github.com/CSC-510/Course/blob/master/Materials/Docker.md) from SE class

Once docker is installed successfully, compose can be installed using

For alternate options, check out [docker compose install](https://docs.docker.com/compose/install/) page on the official website
```
pip install docker-compose
```
#### Motivation - what can we do with docker compose?
Docker compose makes it easier for a user to recreate - deploy and run - any application that uses the microservice architecture style of development. 

Docker eliminates the "run on my machine" by containerizing apps and making it possible to run isolated containers. Docker-compose helps do the same for a multi-container applications that are complex and rely on many containerized services. 

#### Benefits and Use cases
* Makes it easy to set up development, test, staging environments for CI workflows.
* Automated Testing - easy to create and destroy containers
* Recreates only changed containers - so faster in spinning and starting services
* Docker-compose.yml file is easy to write and read
* variables, and key words available in `docker-compose.yml` file help define constraints such as port numbers, networks easy
* When combined with Swarm mode can run multi-container applications in multiple hosts (distributed environment)

![benefits](https://github.ncsu.edu/smirhos/CSC519-TechTalks/blob/master/C1.PNG "Traditional Docker versus Compose")

#### Example
##### Instructions

##### Screencast
View our screen cast [here]()
##### Slides
To look at the [presentation](https://docs.google.com/presentation/d/13g7WY1_OfYk84QamNIe2iTqI1DCcC5oD0IgiulQvt0w/edit#slide=id.gc6f90357f_0_0) slides

#### Related Concepts
![Comparison](https://github.ncsu.edu/smirhos/CSC519-TechTalks/blob/master/C2.PNG "Compare with Kubernetes")
