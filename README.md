# go-templ-vm-deploy
A simple example of deploying go + templ to a VM using ansible.

## Usage 

```bash
cd deploy
ansible-playbook playbook.yaml -i hosts
```

Copy the deploy folder to your project and update for your use case. 

* Check the values in `deploy/default_vars.yaml` and ensure that match your project
* Update the `deploy/hosts` with your connection details

