Use this command to obtain the repository:

```
git clone --recurse-submodules https://github.com/DLLarson/my-ansible-nasmedia.git
```

Upon first checkout run the `apply-patches.sh` script to fix features either
missing or broken in the current `ansible-nas` submodule.

Use this command to run the playbook:

```
./run-ansible.sh
```

Provide the SUDO password to the first prompt and then enter the Ansible vault
password in the next prompt.

