# Fedora workstation config

Ansible playbooks for maintaining my "zendora" workstation. The base OS is
Fedora 29 Core.

## Usage

Create `.vaultpass` file containing ansible-vault password. It is stored in my
1password account. SHA1 hash is 75d6a247c3aa70615710746a2680d9b9100960f9.

Run the playbooks:

```console
$ ansible-playbook bootstrap.yml
$ ansible-playbook -K system.yml
```
