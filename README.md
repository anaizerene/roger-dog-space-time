roger-dog-space-time </br>
Azure AI first workspace notes and raw code with step-by-step instructions </br>

## Setting up your Azure environment </br>
To start, create a notebook called _test.ipynb_ and make sure that it is working under the latest kernel version of Azure ML. Then type in the following code in the noteboook shell:</br>

_import tensorflow as tf_ </br>
_print("TensorFlow Version: " + tf.__version__)_ </br>

You will see error messages because the following pertains to GPU when we are using CPU. </br>

After, stop running the compute instance to *avoid extra charges.* </br>

## Deployment strategies to enhance performance, cost and scalability of your solution. </br>

### Scalability </br>
the ability to dynamically adjust computing resources like processing power, storage, network bandwidth to handle varying worklooads or user traffic demands. Being able to efficiently change the scale of resources ensures optimal performance whilst being cost-effective. </br>
> Azure Kubernetes Service *AKS* supports autoscaling, load balancing, and orchastrating different container instances. </br>
> Azure Batch offers a scalable solution that allows you to distrubute workloads across many virtual machines _if_ your deployment involves processing large volumes of data, or parellel execution of multiple models. </br>

### Deployment speed </br>
the faster you can deploy your model especially when quick decisions/real-time predictions need to be made, the quicker you can start gathering insight and adjusting your strategy/approach based on real-world performance. </br>
> Azure Machine Learning service *AML* offers a streamlined way to deploy models with minimal steup time. It supports deploying models as RESTful web services, allowing for rapid deployment and easy integration into existing applications. *AML* is suggested as it is much more simple and easy to use.
> *AKS* deploys containerized models, great for those in need of high availability and rapid scaling. However, you need to setup Kubernetes and be familiar with it as a service. </br>

### Ease of use <br>
complexity can hinder productivity and overall succes of your project. Keeping things simple is essential, so select an option that aligns with your team's expertise and project requirements. </br>
> *AML* low/no-code environment allows easy deployment with a graphical interfact, similiar to Tableau. Ideal for teams that do not have deepDevOps/cloud computing expertise. </br>
> *Azure App Service* is a straightforward option to deploy web applications and APIs. This is helpful if your model needs to be a part of a web-based application. </br>

### Cost Efficiency

### Updates and Maintenance

### Security and compliance
