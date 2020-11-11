# Terraform and Ansible Setup in GCP
Complete infrastructure on GCP using Infrastructure as a Code.

## Pre-reqs

* Ansible
* Terraform

| Cloud         | Requirements                           | Operating System                                 |    Region      |
| ------------- |:--------------------------------------:|:------------------------------------------------:|----------------|
| GCP           | gcloud cli, Apache-Libcloud(==1.2.0)   | Ubuntu 14.04 (ubuntu-1404-trusty-v20170703)      | us-east1-b     |

## The Design

Using infrastructure as Code tools. Let's create a 2 tier architecture setup consisting of two different tools, Terraform and Ansible.Terraform is used in order to provision the required instances on Cloud in this case GCP. Whereas, ansible is used to configure our application.

![arch2](https://user-images.githubusercontent.com/8342133/28283464-6c37d870-6b4b-11e7-9cf0-ac46aed9c594.png)

## The Setup

* [Terraform](#terraform)
* [Ansible](#ansible)

## Sample Video Demonstrations

Sample video output can be found out for Google Cloud Platform [here](https://youtu.be/EE1Z_9F98vU) :

<a href="http://www.youtube.com/watch?feature=player_embedded&v=EE1Z_9F98vU" target="_blank"><img src="http://img.youtube.com/vi/EE1Z_9F98vU/0.jpg" alt="IMAGE ALT TEXT HERE" width="530" height="360" /></a>

### GCP Terraform

Click link below for detailed GCP instructions on Terraform and Ansible setup in GCP.

* [GCP-Terraform](#gcp-terraform)

##### [GCP-Terraform](#gcp-terraform)

1. We use a security key in JSON format in order to use the resources in GCP. To generate a security key follow:

**Google Cloud Dashboard -> IAM & Admin -> Service Accounts -> Choose a Service Account -> Options -> Create Key**

