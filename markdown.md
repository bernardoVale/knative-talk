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

1 - Using less resources (scale to 0)
2 - Testing a new version
3 - Spliting traffic 
4 - Build Process CI/CD
---
class: top, left, fit-image
layout: false
background-image: url(http://localhost:8000/images/microservices.png)

# Microservices / Serverless

???
1 - Observability = Logging and tracing
2 - Microservices / Serverless (tracing,
3 - Traffic Management
4 - Security (intra-service communication / intra-service auth/auth)

---
# What is Knative ?

A new set of primitives to build/deploy Kubernetes Apps 

???
Um grupo de componentes onde
Cada componente foi desenvolvido pensando em resolver padrões comuns e trazendo melhores práticas de applicações bem sucedidas
--

Current components:

- Build
- Serving
- Eventing

???
Esses componentes estão focados em resolver tarefas comuns (exemplos que trouxemos acima)


---
class: center, middle
# Knative Build

???
Build orchestration
---

# Knative Serving


.middle[![knative](http://localhost:8000/images/serving-model.png)]

---

# Eventing

