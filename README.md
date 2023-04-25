[![collection l3d.avahi](https://ansible.l3d.space/svg/l3d.avahi_ansible-collection_collection.svg)](https://galaxy.ansible.com/l3d/avahi)
[![Maintainance](https://ansible.l3d.space/svg/l3d.avahi_maintainance_collection.svg)](https://ansible.l3d.space/#l3d.avahi)
[![License](https://ansible.l3d.space/svg/l3d.avahi_license_collection.svg)](LICENSE)

 Ansible Collection - l3d.avahi
============================

This is the Ansible Collection ``l3d.avahi``.
Here are all our ansible roles for installing git server.

## Ansible Roles in l3d.avahi
+ [![l3d.avahi.client](https://ansible.l3d.space/svg/l3d.avahi.client_ansible-role.svg)](https://galaxy.ansible.com/l3d/avahi_client)
+ [![l3d.avahi.daemon](https://ansible.l3d.space/svg/l3d.avahi.daemon_ansible-role.svg)](https://galaxy.ansible.com/l3d/avahi_daemon)

## Using this Collection
You can install the collection using ansible-galaxy by running:
```bash
ansible-galaxy collection install l3d.avahi
```

Or you could clone this collection in your local ansible project for example to ``collections/ansible_collections/l3d/avahi/``. Make sure you checkout [git submodules](https://git-scm.com/docs/git-submodule) too. Example:
```
# Clone git Repo with submodules to specified path
git clone --recursive https://github.com/roles-ansible/ansible_collection_avahi.git collections/ansible_collections/l3d/avahi/

# change directory
cd collections/ansible_collections/l3d/avahi/

# optionally init git submodules
git submodule update --init --recursive

# optionally install all requirements
ansible-galaxy install -r requirements.yml
```

You can also list a collection in ``requirements.yml``:
```yaml
---
collections:
  - name: l3d.avahi
    version: ">=0.1.2"
```

