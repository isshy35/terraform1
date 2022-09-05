
# An Ultimate Terraform Hands-on Labs 



![My image](images/wordle.png)

Terraform Labs brings you tutorials that help you get hands-on experience using Terraform, Kubernetes & Cloud. Here you will find complete documentation of labs and tutorials around Terraform CLI, Configuration Language, sub-commands, providers, Registry and much more..

#  Getting Started

- Fork this repository
- Read the material in the Overview
- Work on the terraform beginners track

# Terraform Overview

- [Getting Started: Why, What & How about Terraform?](getting-started/README.md) 
   - [The problem of provisioning everything manually](getting-started/the-problem.md)
   - [The concept of Infrastructure as a Code (IaC)](getting-started/iac.md)
   - [Where terraform comes in?](getting-started/terraform.md)
   - [Use cases of Terraform](getting-started/use-cases.md)


# Terraform Beginners Track

## Installing Terraform

  - [MacOS](beginners/os/mac/README.md)
  - [Linux](beginners/os/linux) 
  - [Windows](beginners/os/windows)
  

## From Terraform INIT To APPLY

  - [Terraform providers](beginners/providers/Terraform_Providers.md)
  - [Terraform resources](beginners/resources/Terraform_Resources.md)
  - [Variable Resources](beginners/resources/variables/README.md)
  - [Output Resources](master/beginners/resources/output/README.md)
  - [Terraform CLI](beginners/CLI/README.md)
  - [Init-plan-apply !](beginners/init-plan-apply/README.md)

## Setting up Cloud Account

As you could need an account in each of cloud providers listed below it is advised that you signup for the free accounts (or trial accounts). You can also use your own account if you already have one. Though be mindful that the resources created though for a short time will incure costs.

> ATTEMPT AT LEAST 1 CLOUD PROVIDER PATH

#### Azure
  - [Create a free / trial account](https://azure.microsoft.com/en-gb/free/)
  - [Getting started with Terraform in Azure](beginners/azure/README.md)
  - [Create a Storage account and Host a static website in Azure](beginners/azure/storageAccount)  
  - [Create AKS Cluster with Container Monitoring](beginners/azure/aks_cluster)
  - [How to use Modules](beginners/azure/module_example)
  
#### AWS
  - [Create a free / trial account](https://aws.amazon.com/free/?trk=ce1f55b8-6da8-4aa2-af36-3f11e9a449ae&sc_channel=ps&s_kwcid=AL!4422!3!433803620870!e!!g!!aws%20free%20account&ef_id=CjwKCAjwvNaYBhA3EiwACgndgrkV7SFWo45WCTf5KtR5y-GSDG0Nh6E2dG4w5iFSthHN_7kmV5MdMhoCocEQAvD_BwE:G:s&s_kwcid=AL!4422!3!433803620870!e!!g!!aws%20free%20account&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all)
  - [Deploy your AWS EKS cluster with Terraform](beginners/aws/eks)

#### GCP
  - [Create a free / trial account](https://cloud.google.com/free)
  - [Setting up Terraform for Google Cloud Platform](beginners/gcp/README.md)
