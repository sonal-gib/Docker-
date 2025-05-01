Container -A container is a lightweight, standalone, and executable software package that includes everything needed to run a piece of software—code, runtime, libraries, and system tools. 
Container is very light weight in nature 



Why container is light weight in nature?
Ans- Because they do not have full OS ,they use the resources from base OS, or on which they are running.

Common Container Tools:
Docker – The most popular container platform.

Podman – A Docker alternative, often used in Red Hat environments.

Kubernetes – Orchestrates many containers across clusters of machines.



Install Docker:

A very detailed instructions to install Docker are provide in the below link

https://docs.docker.com/get-docker/

For Demo,

You can create an Ubuntu EC2 Instance on AWS and run the below commands to install docker.

sudo apt update
sudo apt install docker.io -y

Start Docker and Grant Access
A very common mistake that many beginners do is, After they install docker using the sudo access, they miss the step to Start the Docker daemon and grant acess to the user they want to use to interact with docker and run docker commands.

Always ensure the docker daemon is up and running.

A easy way to verify your Docker installation is by running the below command

docker run hello-world
