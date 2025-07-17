## Segura® PAM Ansible Collection

The **Segura® PAM Ansible Collection** provides Ansible modules for interacting with the Segura® PAM Core module.

Hosted in [galaxy.ansible.com/senhasegura](https://galaxy.ansible.com/ui/namespaces/senhasegura/)


### Requirements

- Segura® Platform with the PAM Core module enabled


### Installation

In your terminal, run the following command

```bash
ansible-galaxy collection install senhasegura.pam
```


### Modules

**senhasegura_device**

With this module you can create, update and deactivate devices in Segura® PAM Core module

[Detailed documentation](https://github.com/senhasegura/ansible-pam-collection/blob/main/docs/senhasegura_device.md)

**senhasegura_credential**

With this module you can create, update and deactivate credentials in Segura® PAM Core module

[Detailed documentation](https://github.com/senhasegura/ansible-pam-collection/blob/main/docs/senhasegura_credential.md)

**senhasegura_credential_info**

With this module you can get informations about a credential, including your password

[Detailed documentation](https://github.com/senhasegura/ansible-pam-collection/blob/main/docs/senhasegura_credential_info.md)


---

## Author information

- Lucas Fraga (@lfraga)
- James Miranda (@jameswpm)
