# KOPS AWS Cluster Creation
Basic bash script for creating a KOPS cluster in AWS

## Motivation
When creating a basic dev infrastructure for our company, we struggled to find easy / cheap ways of running Kubernetes on AWS. EKS is easy to
get started with but can get expensive very quicky and we wanted the ability to easily tear up and down our infrastructure.

The scripts here have been borrowed from dvarcik's course and were adapted by me to get infra set up easily

## Why KOPS?
KOPS Was a great framework to use when creating our clusters as its platform agnostic and proven. Its an easy and cheap way to get started with Kubernetes in AWS.

## Production Ready?
We currently use this cluster in our staging environment and have encountered very few issues. However, it is by no means production ready and has a lot of work to do in order to get to that point.

## Features

### Environment Setup
All folders regarding this can be found in the `env_setup` folder.
### Cluster Creation
All folders regarding this can be found in the `create` folder.
### Cluster Deletion
All folders regarding this can be found in the `delete` folder.
