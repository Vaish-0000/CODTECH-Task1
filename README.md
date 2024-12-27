Name: Vaishnavi R
Company: CODTECH IT SOLUTIONS
ID: CT080D673
Domain: DevOps
Duration: December 12th to January 12th,2025
Mentor: Muzammil
Overview of the Project: Infrastructure as Code with Terraform
Project Title: Infrastructure as Code (IaC) with Terraform

Objective: The objective of this project is to leverage Terraform for automating the provisioning, management, and teardown of cloud infrastructure on AWS. Terraform is an Infrastructure as Code (IaC) tool that enables you to define cloud resources in configuration files, ensuring consistency, version control, and repeatability in the creation and management of your infrastructure.

What is Infrastructure as Code (IaC)?
Infrastructure as Code (IaC) is the practice of managing and provisioning computing infrastructure (like servers, databases, networking, etc.) through machine-readable configuration files, rather than through manual processes. The key benefits of IaC include:

Consistency: Ensure that the infrastructure is created and configured exactly as defined in code.
Version Control: Infrastructure configurations can be version-controlled and rolled back if needed.
Automation: Automate the process of infrastructure provisioning, making it faster, reliable, and scalable.
Scalability: Easily scale your infrastructure by simply modifying the code and reapplying the changes.
Terraform is one of the most popular IaC tools because of its open-source nature, ease of use, and support for multiple cloud providers like AWS, Azure, and Google Cloud.

What is Terraform?
Terraform is an open-source IaC tool developed by HashiCorp that allows you to define, provision, and manage infrastructure resources through declarative configuration files. Terraform supports multiple cloud providers (AWS, Azure, GCP, etc.), on-premise systems, and other services.

Key features of Terraform:

Declarative language (HCL - HashiCorp Configuration Language): Terraform uses HCL to describe the desired state of infrastructure.
State Management: Terraform maintains a state file to keep track of the resources it manages, ensuring infrastructure is created and managed correctly.
Plan and Apply: Terraform allows you to preview (plan) the changes before applying them, providing a safer way to manage infrastructure.
Providers: Terraform uses providers (e.g., AWS, Azure) to interact with different cloud services.
Steps in the Project
The project will be structured around the following key tasks:

Setting Up Terraform:

Install Terraform on your local machine or a development environment.
Set up AWS credentials to allow Terraform to interact with your AWS account.
Defining Infrastructure as Code (IaC):

Create Terraform configuration files using the .tf extension. These files describe the cloud resources you wish to create and manage.
The configuration files will define resources such as AWS EC2 instances, security groups, VPCs, etc.
Provisioning Infrastructure:

Run terraform init to initialize your working directory and download the necessary provider plugins.
Run terraform plan to preview the infrastructure changes Terraform will make (like creating an EC2 instance, VPC, etc.).
Run terraform apply to apply the changes and provision the infrastructure on AWS.
Managing Infrastructure:

Once the infrastructure is provisioned, you can update it by modifying the Terraform configuration files.
Run terraform plan and terraform apply again to apply changes.
Teardown Infrastructure:

To destroy the infrastructure and clean up resources, run terraform destroy.
This command ensures that all resources created by Terraform are properly decommissioned, helping to prevent unnecessary charges on your AWS account.
