# k8sdemo

This is just a modified play around repo from https://github.com/AOEpeople/k8sdemo
This was presented on the Mage Unconference in Cologne 2017 by Fabrizio and Bastian. 

Continuous Delivery Live Demo with Kubernetes, Jenkins, Terraform, AWS

- Infrastructure as Code
- Terraform
- Setup Jenkins
- Jenkins Pipeline
- Build inside a container
- Container as artifact
- Immutable Deployments
- AWS
- VPC
- Autoscaling

### Tools
- Kops
- Create Service (+ELB+DB)
- Deploy via Jenkins
- Continuous Delivery


## Test

kops create cluster --zones=us-east-1c useast1.dev.example.com
