# Ansible Collection - cloud.aws_roles

This repository hosts the `cloud.aws_roles` Ansible Collection.

The collection includes a variety of Ansible roles and playbook to help automate the management of resources on AWS.

## Included Content

<!--start collection content-->
### Roles

| Name                            | Description                         |
| ------------------------------- | ----------------------------------- |
| cloud.aws_roles.networking      | A role to manage VPC configuration. |
| cloud.aws_roles.virtual_machine | A role to managed EC2 instances.    |

### Playbooks
| Name                     | Description                             |
| ------------------------ | --------------------------------------- |
| cloud.azure_roles.webapp | A playbook to create a webapp on Azure. |
<!--end collection content-->

## Installation and Usage

### Installing the Collection from Ansible Galaxy

Before using the aws_roles collection, you need to install it with the Ansible Galaxy CLI:

    ansible-galaxy collection install cloud.aws_roles

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml`, using the format:

```yaml
---
collections:
  - name: [cloud.aws_roles](https://github.com/Ansible-Incubated-Content/cloud.aws_roles.git)
    type: git
    version: main
```

# License
GNU General Public License v3.0 or later

See [LICENCE](https://github.com/Ansible-Incubated-Content/cloud.aws_roles/blob/main/LICENSE) to see the full text.