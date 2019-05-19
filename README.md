# Terraform - LiL

Learning CourseWork

# Sequential steps
- install terraform
- initiate 'connection.tf' file
- `$ terraform init`
- add the requirements into 'resources.tf' file
- `$ terraform plan` (soft-check for the availability/resources)
- `$ terraform apply` (apply the configuration as defined in resources.tf)# terraform-lil

# Some useful commands 
`$ terraform validate` - confirm *.tf files are correct
`$ terraform fmt` - formate/indent all *.tf files properly
`$ terraform state` - check the state of the resource. Help for more info
`$ terraform graph` - explore more about this

'variables.tf' central place to define all the reusable variables.
'$ terraform apply --var-file=<file-name-for-env>'
