# Terraform and Ansible Setup in GCP
Complete infrastructure on GCP using Infrastructure as a Code.

## Pre-reqs

* Ansible
* Terraform

| Cloud         | Requirements                           | Operating System                                 |    Region      |
| ------------- |:--------------------------------------:|:------------------------------------------------:|----------------|
| GCP           | gcloud cli, Apache-Libcloud(==1.2.0)   | Ubuntu 14.04 (ubuntu-1404-trusty-v20170703)      | us-east1-b     |

## My Design

Using infrastructure as Code tools. Let's create a 2 tier architecture setup consisting of two different tools, Terraform and Ansible.Terraform is used in order to provision the required instances on Cloud in this case GCP. Whereas, ansible is used to configure our application.

![arch2](https://user-images.githubusercontent.com/8342133/28283464-6c37d870-6b4b-11e7-9cf0-ac46aed9c594.png)
