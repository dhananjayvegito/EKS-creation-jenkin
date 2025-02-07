# EKS-Terraform-Jenkins
EKS-Terraform-Jenkins

Install AWS cli.
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

Prior to this you need to export or configure AWS account.

aws eks update-kubeconfig --region us-east-1 --name dhananjay-cluster  ## through this you can enter in kuberneties.
