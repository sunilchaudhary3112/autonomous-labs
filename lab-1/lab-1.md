---
layout: default
title: Lab 1 Your DB in the cloud (ATP)
---

# 🚀 Lab 1: Your DB in the cloud (ATP)

Use this as a template to build make your lab guide. If you have any resources like `.csv` files or `.zip` files they can be put in the according lab folder in the repository and downloaded like this.

[Download lab resources](https://alpsteam.github.io/autonomous-labs/lab-1/some-zip-file.zip){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } 

## Table of contents

* [Prerequisites](#prerequisites)
* [Introduction to your lab](#introduction-to-your-lab)
* [Lab guide](#lab-guide)
   * [Setting up repository](#setting-up-repository)
   * [Wercker CI/CD pipelines](#wercker-pipelines-for-continous-integration)
   * [Deploying to Kubernetes cluster](#deploying-to-kubernetes-cluster)
   * [Some more steps](#some-more-steps)
* [Next steps](#next-steps)
* [Issues](#issues)


## Prerequisites

- An Oracle Cloud Account
- Right permissions
- This lab will roughly require 200€ in Universal Cloud Credits
- etc.

## Introduction to your lab

Here we can write about the technology and why its cool. E.g. describe what is APEX, with some links and perhaps one or two screenshots. Or why are microservices popular and why should you do it with Helidon and Oracle Managed K8s.

If you want to include an image, the image should be in a folder `/images` and can be shown like this:

![Oracle DB with Microservices](/images/oracle-db-microservices.png)

# Lab guide

## Setting up repository

This is where the tutorial starts with all steps of the lab. Divide the lab into 3-10 chapters. In each chapter describe all steps, including some screenshots.

All lab resources, e.g. CSVs, code, etc. should be included in the repository.

## Wercker pipelines for Continous Integration

Should there be a need to highlight code it can be done like this.

```java

public class GreetService {
  @GET
  @Path("/greet")
  public String getMsg() {
    return "Hello World!";
  }
}

```

## Deploying to Kubernetes cluster

.....

## Some more steps

......

## Next steps

Here we can provide some next steps. We should give ideas what the lab participant can do next with the service. Oracle has lots of good resources (blogs etc.) thank we can link. 
