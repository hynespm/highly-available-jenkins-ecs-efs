## Description : Cloudformation template that creates an ECS cluster for a Jenkins master, along with an elastic file system for the storage of the Jenkins configuration

## Author : Patrick Hynes

##Introduction

This repository is a cloudformation template used to setup an highly available Jenkins Build Server (https://jenkins.io/) using a combination of the Elastic Container Service and the Elastic File System (http://docs.aws.amazon.com/efs/latest/ug/getting-started.html). The application deployed using the Jenkins Docker container listed on Dockerhub (https://hub.docker.com/r/jenkinsci/jenkins/). The jenkins master server should be able to leverage its own ECS cluster or others to run jobs on Jenkins slaves created in the ECS service as tasks.

## Feedback

If you wish to contact me with feedback, please contact via email or skype

* @email: hynespm@gmail.com
* Skype: hynespm