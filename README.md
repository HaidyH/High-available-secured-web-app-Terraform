# High-available-secured-web-app-Terraform

1- clone this repo

https://github.com/HaidyH/High-available-secured-web-app-Terraform.git

2- Create your own key-pair and use in servers/main.tf

3- Make sure to pass your credentials correctly in main.tf file provider block

4- Comment the backend in RemoteStateFile.tf and change S3 name to a unique one

5- Make sure you Have installed latest version of Terraform and run the following commands inside the project directory

terraform init 
terraform apply

6- uncomment the backend and apply step 5 again
