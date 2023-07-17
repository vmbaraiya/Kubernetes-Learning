# Kubernete background

Kubernete is an *application orchestrator*. For the most part, it orchestrates containerized cloud-native microservice apps.

Kubernete deploys and manages (orchestrate) applciations that are packaged and run as containers (containerized) and that are built in a was (cloud native microservices) that allow them to scale, self heal, and be udpated in line with modern cloud like requirements.

## what is an orchestrator

An *Orchestrator* is a system that *deploys* and *manages* applications. It can deploy your applications and dynamically respond to changes. For example, Kubernetes can:

- Deploy your application
- scale it up and down dynamically based on demand
- self heal it when things break
- perform zero-downtime rolling updates and rollbacks
- Lots more....

And the best part about Kubernetes... it does all of this orchestration without you having to supervise or get involved.

## Containerised app

A *Containerized applciation* is an app that runs in a container.

Containers are just the next iteration of how we package and run apps. As such, they're faster, more lightweight, and more suited to modern business requirements than servers and virtual machines.

## What is cloud native app
A *Cloud Native Applciation* is one that's designed to meet cloud like demands of auto-scaling, self-healing, rolling updates, rollbacks and more.

It's important to be clear that cloud native apps are not applications that will only run in the public cloud, Yes, they absolutely can run on public clouds, but they can also run anywhere thatyou have kubernetes, even your on-premises datacentres.

## What is microservice app
A *microservices app* is built from lots of small, specialised, independent parts that work together to form a meaningful applciation. For example, you might have an e-commerce app comprising all of the following small, specialised, independent components:
- web front end
- catalog service
- shopping cart
- Authentication service
- Logging service
- persistent store

As each of these features is developed and deployed on its own small app, or small service, we call each one a microservice. 
