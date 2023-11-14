# Creating, managing, and deployment of a K8s cluster with auto scaling and auto healing for a Multi-tier web app

This project demonstrates how to create, manage, and deploy a Kubernetes cluster with auto scaling and auto healing capabilities for a multi-tier web application. The application stack consists of Memcached, Rabbitmq, and Tomcat, which have been containerized. The project also uses Docker Hub as the container registry and Git as the version control system.

![Screenshot (307)](https://user-images.githubusercontent.com/70194383/230267454-71f36720-10b6-4e6c-8336-dbad800d62b8.png)


## Project Scenario

The multi-tier application stack has been containerized and needs to be tested before it can be deployed for production use. The requirements for the deployment are that it should be highly available, fault-tolerant, easily scalable, platform-independent, portable, and flexible.

## Technologies and Tools Used

* Kubernetes: Orchestration tool
* Kubernetes cluster
* Docker: Container runtime
* Docker Hub: Container registry
* Git: Version control system
* Memcached: In-memory caching system
* Rabbitmq: Message broker
* Tomcat: Web application server


## Clone this repository to your local machine:
~~~
https://github.com/SkyrunnerOO7/Managing_and_deployment_k8s_cluster_for_a_Multi-tier-web-app.git
~~~


## Steps
1. Create a Kubernetes cluster with the required number of nodes based on your requirements.
2. Containerize the application stack and create a Docker image for each container.
3. Verify that the containers are working properly by testing them on your local machine.
4. Push the Docker images to Docker Hub.
5. Create an EBS volume for the DB pod.
6. Label the Kubernetes nodes with the zone name.

7. Create Kubernetes definition files for each container, specifying the container image, the number of replicas, the ports to expose, and any required environment variables.

8. Create Kubernetes deployments for each container.

9. Create a Kubernetes service to expose the containers to the internet.

10. Create a Kubernetes secret to store any sensitive information.

11. Create a Kubernetes volume for the DB pod.

12. Test the deployment by accessing the web application.

14. Enable auto scaling and auto healing for the Kubernetes cluster.

15. Monitor the cluster to ensure that it is running smoothly.

16. Once the deployment has been tested and verified, deploy it for production use.

## Contributing
If you would like to contribute to this project, please follow these steps:

1. Fork this repository to your own account.
2. Create a branch from the main branch with a descriptive name.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Create a pull request to merge your changes into the main branch of this repository.
