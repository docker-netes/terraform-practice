terraform init
Initializes Terraform and downloads required providers/modules if not already installed. Does not update existing providers.


terraform init --upgrade
Reinstalls all required providers and updates them to the latest allowed versions.

terraform plan
Shows an execution plan but does not save it. Running it again may generate a different plan.


terraform plan -out main.tfplan
Saves the plan to a file (main.tfplan), ensuring the same changes are applied later.


note: terraform provider is required
