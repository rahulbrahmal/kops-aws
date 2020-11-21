## Cluster Deletion
There are two steps required to create a cluster. First, you need to create all the AWS Resources required in your AWS Account. This includes creating IAM groups and attaching their relevant policies, IAM Users and generating keys. Then you will use this user created to create a new cluster.

### KOPS Cluster Setup
1. Run `sh kops-setup.sh`.
    - This will generate the KOPS Cluster

### AWS Account Setup
1. Run `sh aws-setup.sh`
    - This will generate additional keys so that your environment can access the cluster
