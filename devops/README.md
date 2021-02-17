**Here's a challenge for you!**

We are actively looking for DevOps specialists to join our IT team.

Goal of this challenge is to provide potential candidates with a learning experience using Flinks’ technology stack. It also helps Flinks evaluate current technical knowledge as well as a candidate’s approach to problem solving.

Once you are done please share the GitHub url with us at challenge@flinks.io 

Have fun!

Technologies:
* Container Orchestration - Kubernetes
* Load Balancing - Nginx Ingress Controller
* Containers - Docker
* Web Application - Nginx
* **Bonus**​ Web Application (REST API) - Go

Requirements:
1. Get a local kubernetes cluster up and running using microk8s
   * Enable DNS, Registry and Helm3 services
   * Create a GitHub repo for the challenge in order to host your configuration files and scripts
2. Run a basic website based on a Nginx container
   * URL needs to be: ​**challenge.domain.local**
   * Web service must return ​**Hello Flinks**​ on “/” in a namespace named ​**flinks**
4. Nginx Ingress Controller must be must be installed in namespace ​**ingress-controller** (without using microk8s' ingress service)
5. Website must be highly available (HA) and load balanced using Nginx Ingress Controller
6. Bash script to restore all your configurations into a brand new cluster

Bonus:
7. A second web application pointing to URL ​**challenge-api.domain.local**​ 
   * Use Golang to build a basic CRUD functions API (in-memory, no persistence required)
   * It needs to use the same Load Balancer IP via Nginx Ingress Controller

Validation:
Once objectives have been completed, we will validate Kubernetes yaml configurations in your cluster as well as end result which should be a highly available website once provisioned on a new cluster using your provisioning script.