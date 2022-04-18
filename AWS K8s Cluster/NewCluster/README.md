#New Cluster Using Github Modules#

In this demo I tried to use other modules to defeat the certificate issue I faced with the other module. 
Here I used two files to set my EKS cluster environment. 
1- In the module file I used a module I found on github that sets he VPC and SG.
2- In the cluster file I used a terraform module for EKS 

#Deploying!#
$Terraform init
$Terraform apply 

#Connect to Cluster#
$aws eks --region us-east-1 update-kubeconfig --name my-eks-cluster


