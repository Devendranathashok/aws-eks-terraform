# aws-eks-terraform <br />

Install Terraform using terraform.sh script. <br />
chmod +x terrform.sh <br />
./terraform.sh <br />

![image](https://github.com/Devendranathashok/aws-eks-terraform/assets/29894924/71488fdc-569a-47d3-9987-8097db0a5e95)

terraform -v <br />

![image](https://github.com/Devendranathashok/aws-eks-terraform/assets/29894924/a6aff646-86e2-447f-910e-55bfe14efb10)

Install aws CLI usnig aws-cli.sh <br />

Execute Terraform scripts: <br />
terraform init <br />
terraform plan <br />
terraform apply --auto-approve <br />

Once you create the resource in AWS, Install kubectl. <br />
chmod +x kubectl.sh <br />
./kubectl.sh <br />

To operate k8s from any jumphost do the below steps. <br />
aws configure <br />
YOU HAVE TO ENTER YOUR ACCESS KEY AND SECRET KEY TO ENABLE AWS CLI <br />

Get kube config from EKS by running below command. <br />
aws eks update-kubeconfig --name <your-cluster-name> --region <region> <br />
![image](https://github.com/Devendranathashok/aws-eks-terraform/assets/29894924/8a3b71e8-cf6e-4a39-9f2b-eeaf3ab49993)




