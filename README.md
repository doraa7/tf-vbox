# Deploy multiple VMs in virtualbox using Terraform and Cloud-init

This very simple terraform manifest can deploy multiple VMs in virtualbox. See my blogpost for more information:

https://www.roksblog.de/terraform-virtualbox-provider-terrafarm/

In order to use this code you must have:
1. A machine with Terraform and Virtualbox

In order to run this:
1. clone the git repo
2. cd into the cloned directory
3. run:
```ruby
 terraform init
```
4. run: 
```ruby
terraform plan
```
5. run:
```ruby
terraform apply
```
After the deployment the IPs for the VMs will be displayed.