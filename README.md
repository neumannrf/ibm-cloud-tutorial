# IBM Cloud tutorial

A tutorial for deploying *number-crunching* Python applications to IBM Cloud.

## Scope

This tutorial illustrates typical work-flows and tools in cloud computing, addressing key concepts
and technologies.
By the end of this tutorial everyone should be able to deploy a Python application to the cloud
and have some familiarity with

* IBM Cloud
* GitHub Enterprise
* Docker containers
* Visual Studio Code
* Continuous Delivery
* Kubernetes containers
* Microservice Starter Kits
* Cloud Foundry applications

## Instructions

1. Read [**Installing developer tools and environments**](0-INSTALL.md) and follow the steps.
    1. [Setting up IBM Cloud environment](0-INSTALL.md#setting-up-ibm-cloud-environment)
    1. [Setting up GitHub Enterprise environment](0-INSTALL.md#setting-up-github-enterprise-environment)
    1. [Installing IBM Cloud CLI](0-INSTALL.md#installing-ibm-cloud-cli)
    1. [Installing Docker Community Edition](0-INSTALL.md#installing-docker-community-edition)
    1. [Installing Kubernetes client](0-INSTALL.md#installing-kubernetes-client)
    1. [Installing Visual Studio Code](0-INSTALL.md#installing-visual-studio-code)

1. Read [**Configuring DevOps tools**](1-CONFIGURE.md) and follow the steps.
    1. [Creating a Python Starter Kit](1-CONFIGURE.md#creating-a-python-starter-kit)
    1. [Creating GitHub Enterprise repository](1-CONFIGURE.md#creating-github-enterprise-repository)
    1. [Configuring Continuous Delivery Pipeline](1-CONFIGURE.md#configuring-continuous-delivery-pipeline)

1. Read [**Playing with your Python application**](2-PLAY.md) and follow the steps.
    1. [Cloning the repository](2-PLAY.md#cloning-the-repository)
    1. [Testing the example implementation](2-PLAY.md#testing-the-example-implementation)
    1. [Customizing the example implementation](2-PLAY.md#customizing-the-example-implementation)
    1. [Customizing the example implementation again](2-PLAY.md#customizing-the-example-implementation-again)
    1. In the end, your file should look like [`app/custom-health.py`](app/custom-health.py)

1. Read [**Developing a number-crunching application**](3-DEVELOP.md) and follow the steps.
    1. [Generating a Swagger API documentation](3-DEVELOP.md#generating-a-swagger-api-documentation)
    1. [Exploring the Swagger API documentation](3-DEVELOP.md#exploring-the-swagger-api-documentation)
    1. [Creating number-crunching services](3-DEVELOP.md#creating-number-crunching-services)
    1. [Configuring Python deployment environment](3-DEVELOP.md#configuring-python-deployment-environment)
    1. [Linking number-crunching services to API resources](3-DEVELOP.md#linking-number-crunching-services-to-api-resources)

1. Read [**Containerising the Python application**](4-CONTAINERISE.md) and follow the steps.
    1. [Setting up a private registry namespace](4-CONTAINERISE.md#setting-up-a-private-registry-namespace)
    1. [Creating a new Kubernetes-based toolchain](4-CONTAINERISE.md#creating-a-new-kubernetes-based-toolchain)
    1. [Deploying a container with Continuous Delivery Pipeline](4-CONTAINERISE.md#deploying-a-container-with-continuous-delivery-pipeline)
    1. [Accessing the containerised application](4-CONTAINERISE.md#accessing-the-containerised-application)
    1. [Deploying a container manually using the command-line](4-CONTAINERISE.md#deploying-a-container-manually-using-the-command-line)
