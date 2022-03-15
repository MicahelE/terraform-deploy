# Getting Started with Amazon EKS using Terraform

More resources:

Terraform provider for AWS [here](https://www.terraform.io/docs/providers/aws/index.html) <br/>
## Login to Amazon

```
# Access your "My Security Credentials" section in your profile. 
# Create an access key

aws configure

Default region name: us-east-2
Default output format: json
```
## Terraform Amazon Kubernetes Provider 

Documentation on all the Kubernetes fields for terraform [here](https://www.terraform.io/docs/providers/aws/r/eks_cluster.html)

```
cd terraform-deploy

terraform init

terraform plan
terraform apply

```
# Clean up 

```
terraform destroy
```