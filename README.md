# aws-eks-terraform

Install Terraform using terraform.sh script.
chmod +x terrform.sh
./terraform.sh

![image](https://github.com/Devendranathashok/aws-eks-terraform/assets/29894924/71488fdc-569a-47d3-9987-8097db0a5e95)

terraform -v

![image](https://github.com/Devendranathashok/aws-eks-terraform/assets/29894924/a6aff646-86e2-447f-910e-55bfe14efb10)

Install aws CLI usnig aws-cli.sh

Execute Terraform scripts:
terraform init
terraform plan
terraform apply --auto-approve

Once you create the resource in AWS, Install kubectl.
chmod +x kubectl.sh
./kubectl.sh

To operate k8s from any jumphost do the below steps.
aws configure
YOU HAVE TO ENTER YOUR ACCESS KEY AND SECRET KEY TO ENABLE AWS CLI

Get kube config from EKS by running below command.
aws eks update-kubeconfig --name <your-cluster-name> --region <region>
![image](https://github.com/Devendranathashok/aws-eks-terraform/assets/29894924/8a3b71e8-cf6e-4a39-9f2b-eeaf3ab49993)




