# deploy-nodeapp-terraform-ansible

## Steps to deploy
### Configure AWS 
```hcl
Replace this credentials in main.tf

provider "aws" {
  region     = "AWS_REGION"
  access_key = "AWS_ACCESS_KEY"
  secret_key = "AWS_SECRET_KEY"
}
```

## Command to execute
### Initialize terraform
```hcl
terraform init
```

### Run terraform script
```hcl
terraform apply

Enter Name of the SSH key pair
```

### Destroy all resouces
```hcl
terraform destroy
```