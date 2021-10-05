---
layout: post
read_time: true
show_date: true
title:  High Level microservices Web Architecture using Azure PaaS solutions only.
date:   2021-01-25 13:32:20 -0600
description: For those who want to quickly get started on developing their microservices without having to worry about the infrastructure provisioning over head
img: posts/azure-architecture/highleveldesign-ewbapplication-microservice-2021-06-1574945PM.png
tags: [azure, architecture]
author: Sumit Asok
github: sumitasok/references
mathjax: yes
---

For those who want to quickly get started on developing their microservices without having to worry about the infrastructure provisioning over head, below is the easy and secure architecture.

![high level microservice web architecture](/assets/img/posts/azure-architecture/highleveldesign-ewbapplication-microservice-2021-06-1574945PM.png)


## Application Gateway (WAF)
- Host
- Backend
- Listener
- Rule

(Insert diagram here)

## Auth termination at APIM

How to authenticate using Auth0 on APIM.

## App Services

How to connect DevOps for CI/CD.

## Storage

### Postgres

Always use hosted postgres by Azure for reduced maintenance.

### BlobStorage