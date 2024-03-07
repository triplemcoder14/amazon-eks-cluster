# amazon-eks-cluster

code sample for how to create amazon eks cluster using terraform. enabling efficient deployment and management of Kubernetes workloads on AWS infrastructure using terraform

this takes care of provisioning and managing the Kubernetes control plane, worker nodes, networking, and other infrastructure components. and allows the team to focus on developing their application while benefiting from the scalability, reliability, and flexibility of Kubernetes on AWS.

## apply changes

`terraform init`

terraform init command is used to initialize a new or existing Terraform configuration. this command downloads the required provider plugins and sets up the backend for storing state.

` terraform plan`

the terraform plan command is used to create an execution plan for the Terraform configuration. This command shows what resources Terraform will create, modify, or delete when applied.

` terraform apply`

the terraform apply command is used to apply the Terraform configuration and create or modify resources in the target environment.

to export Kubernetes context you can use aws eks … command; just replace region and name of the cluster

`aws eks --region us-east-1 update-kubeconfig --name eks_cluster`

feel free to contribute
