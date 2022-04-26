> This role is not meant to be shared. It is only used by myself.
> I use this role in my playbooks by adding the repo as a Git submodule.

# Ansible Role `terraform`

Role that installs and configures Terraform.

- <https://github.com/hashicorp/terraform>

## FAQ

### How to bump the version of Terraform?

Go into [tasks/main.yaml](./tasks/main.yaml) and adjust the version in the
task "Install Terraform with asdf".
