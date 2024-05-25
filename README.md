# terraform-lab

To init terraform state
```shell
terraform init
```

To check the current terraform file content
```shell
terraform plan
```

To provision infra according to terraform file
```shell
terraform apply --auto-approve
```

To delete all the things created from running `terraform apply`
```shell
terraform destroy
```

To show the current state of provisioned infra
```shell
terraform state list
```
