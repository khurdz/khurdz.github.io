# All Day DevOps 2020 - Modern Infrastructure

## How to build, scale and maintain 30 public Terraform modules with over 30 million provisions

* Speaker : Anton Babenko, Terraform Grandmaster
  * [terraform-community-modules](https://github.com/terraform-community-modules) + [terraform-aws-modules](https://github.com/terraform-aws-modules)
  * [antonbabenko/pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform) — clean code, documentation, and more
  * [serverless.tf](https://serverless.tf/) — Doing serverless on AWS with Terraform
  * [antonbabenko/modules.tf-lambda](https://github.com/antonbabenko/modules.tf-lambda) — generate Terraform code from visual diagrams
  * [antonbabenko/terragrunt-reference-architecture](https://github.com/antonbabenko/terragrunt-reference-architecture) — Terragrunt reference architecture
  * [www.terraform-best-practices.com](https://www.terraform-best-practices.com/)
  * [bit.ly/terraform-youtube](bit.ly/terraform-youtube) — "Your weekly dose of #Terraform" & "Terraform tools review"
* Some notes about Terraform Best Practices
  * Importance of tooling (tflint, hub, semtag, code-reviews)
  * Focus on resource modules to allow composition instead of bigger infrastructure modules (eg. Cloudfront+S3+ACM modules instead of a "static website" module)
  * Need for terratest ? Not always, a plan/apply is enough for basic or advanced use cases
* [Slides](assets/terraform-aws-modules-november-2020.pdf)

&nbsp;

## Immutable Deployments: The New Classic Way for Service Deployment

* Quick recap of what must be a classic must-know as of 2020
* [Slides](assets/Immutable-deployments-the-new-classic-way-for-service-deployment.pdf)

&nbsp;

## Ruling Kubernetes on all Cloud Platforms

* A nice reading to kickstart your first k8s clusters on any major Cloud Providers
* It is worth noting that node limits depends on the underlying Cloud Provider
* Prometheus + Thanos = <3
* [Slides](assets/Ruling-Kubernetes-on-the-Cloud.pdf)

&nbsp;

## Infrastructure as REAL Code with AWS CDK

* CDK is the 2020 hype for IaC
* Some useful resources :
  * [CDK Construct Catalog](https://awscdk.io/)
  * [CDK Patterns](https://cdkpatterns.com/)
  * [CDK8S](https://cdk8s.io/) for defining Kubernetes application using code
  * [Terrastack](https://www.terrastack.io/), a polyglot Terraform supercharged by the CDK
  * [Terraform-CDK](https://github.com/hashicorp/terraform-cdk), another polyglot Terraform supercharged by the CDK
  * [CDK Workshops](https://cdkworkshop.com/)
  * [CDK examples](https://github.com/aws-samples/aws-cdk-examples)
* [Slides](assets/ADDO_Infrastructure_as_real_code_CDK.pdf)
