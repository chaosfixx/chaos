# What is Container Orchestration?

Container orchestration basically focuses on managing containers and their dynamic environments. It is all about managing the lifecycles of containers and it also helps DevOps teams who integrate containers in CI/CD workflow. The Software team uses container orchestration engine for controlling/managing and automating tasks mentioned below:

Containers provisioning and deployment
Availability of containers
Scaling up or down according to spread application load evenly across the host
Movement of containers from one host to another if there is a shortage of resources in a host, or if a host dies
Allocation of resources between containers
Load balancing of service discovery between containers
Health monitoring of containers and hosts

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
