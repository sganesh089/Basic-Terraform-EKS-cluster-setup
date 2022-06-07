# Basic-Terraform-EKS-cluster-setup

This is a basic setup for creating and deploying EKS cluster using terraform.
Used a T2 medium aws ubuntu instance for this project. Initially tried t2 micro instance but it crashed due to low configration i think so! While trying to view the terraform plan the t2 micro instance froze and went into unresponsive mode.
Pre-requistes for this project is a AWS instance with admin configs, AWS cli, Terraform, kubectl installed.

Below Kubernetes clusters were deployed using terraform:

![image](https://user-images.githubusercontent.com/41573564/157556631-aa0c905a-d0c6-4139-91aa-d999702c081e.png)

Destroyed the terraform instances once the setup was over! all clusters were destroyed and terminated the terraform instance to save some costs :P 


Reference file: https://www.fairwinds.com/blog/terraform-and-eks-a-step-by-step-guide-to-deploying-your-first-cluster
