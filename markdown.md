class: center, bottom


.middle[![knative](http://localhost:8000/images/knative.png)]

# Knative Introduction


---


# About me

Learn how you can use Kubernetes to deploy, scale and maintain applications without worrying about how the cluster works
and how all the pieces fit together.


---

# A glimpsy about the history


---
class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/age-1.jpg)

# Data Center Age

???
1 Age = artezanato + om prem servers + bare metal

---

class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/age-2.jpg)

# Hypervisor Age

???
New API, below is commodity
Deploying is easier, python/shell scripts

---
class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/age-3.jpg)

# Configuration Manangment Age

???
Writing chef/puppet code to automate provisioning

---
class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/age-4.jpg)

# Public Cloud Age

???
Yet another new API
immutable infrastructure

---
class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/age-5.jpeg)

# Container Age

???
immutable infrastructure + virtual machines

---
class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/age-6.png)

# Kubernetes Age

???
Another API
Deployment process simple
Scale is simple

SERVERLESS PROBLEM
SCALE TO ZERO
LOGGING

---
class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/microservices.png)

# Microservices / Serverless

???
- Observability = Logging and tracing
- Microservices / Serverless (tracing,
- Traffic Management
- Security (intra-service communication / intra-service auth/auth)

---

# What is Knative


Provide a set of middleware components that are essential to build modern, source-centric, and container-based applications that can run anywhere.

Each of the components under the Knative project attempt to identify common patterns and codify the best practices that are shared by successful real-world Kubernetes-based frameworks and applications. 

Knative components focus on solving many mundane but difficult tasks such as:

???
A set of CDR

---
# Knative Build

- Build
- BuildTemplate
- Builder

???

---

# Build Templates

A reusable set of steps to build a function/app. Each step is a `builder`

???
Builder is just a container 
ClusterBuildTemplates same thing but with cluster level scope
https://github.com/knative/build-templates

---

# Builder

Takes source code +  set of steps or a template to build a function/app

---

# Knative Serving Model


.middle[![knative](http://localhost:8000/images/serving-model.png)]


# Eventing

