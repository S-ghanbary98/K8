# Kubernetes

![](Kubernetes_New.png)

##### What is Kubernetes

- Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications.

## Benefits

- <b>Portability and Flexibility:</b> Virtually works with any type of container runtime. It als works with any type of underlying infrastructure whether public, or private cloud.
- <b>Multi-cloud capability: </b>Kubernetes can host workloads running on a single cloud as well as workloads that are spread across multiple clouds. In addition, Kubernetes can easily scale its environment from one cloud to another.
- <b>Stability: </b>allows you to have rolling updates to change your software without downtime. It is further possible to set up Kubernetes in a way that it supports high availability applications and if you are using the public cloud services of major vendors, you can be pretty sure to reach a very high uptime.
- <b>Load Balancing :</b> Can distributing a set of tasks over a set of resources, with the aim of making their overall processing more efficient.
- <b>Self healing:</b> If failures occur k8 will rectify this by spinning up a new resource to replace the broken one.
- <b>Auto Scaling</b>
- <b>Automatic bin Stacking</b>
- <b>Storage Orchestration</b>


## Drawbacks
- <b>Complex: </b>Kubernetes is infamously known for its complexity. Especially for developers not familiar with infrastructure technologies, it can be very hard to get used to the Kubernetes development workflow.




## Competitors
- Mirantis Cloud Native Suite
- Amazon Elastic Container Service
- Red Hat OpenShift
- Azure Container Instances
- IBM Cloud Kubernetes Service

## Why not to use Kubernetes

- In order to take advantage of its features, developers and IT operators must have knowledge of containers, network, security, portability, resiliency, and Kubernetes itself. To make proper use of its workloads, you should understand how each component works. To manage a cluster, you should understand its architecture, storage, API, and administrative system, which is a lot different from traditional virtualized environments.
- Kubernetes is a platform designed to boost performance and reduce the operational effort of distributed systems. It basically makes a complex scenario, like microservices, less operationally complex. It is best not to use it due to it's complexity If you're not dealing with many applications.

## Use Cases

- <b>Microservices architecture:</b> A use case where you want to deploy a more complicated app with many components that will communicate with one another is a classic scenario for Kubernetes.
- <b>Local servers to cloud:</b> frequently today, as software is migrated from on-prem infrastructure to cloud solutions  First, such a big app working outside the cloud is moved to the same big app in Kubernetes.
- <b> Computing power Balance:</b>  Kubernetes cluster is a good solution to manage the distribution of computing power across multiple computers.
- <b> CI/CD :</b> Kubernetes also brings considerable benefits to Continuous Integration/Continuous Deployment or Continuous Delivery methodology.


## Managed Services

Managed Kubernetes is when third-party providers take over responsibility for some or all of the work necessary for the successful set-up and operation of K8s. Some managed platforms include 

- Google Kubernetes Engine (GKE)
- AWS Elastic Container Service for Kubernetes (Amazon EKS)
- OpenShift

In Short if, we are looking for a way to take advantage of the benefits of Kubernetes with a hands-off approach, a fully managed platform solution is ideal.