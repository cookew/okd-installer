# okd-installer


# How to install ansible with pipx
```
pipx install ansible-core
pipx inject --include-apps ansible-core jmespath
pipx inject --include-apps --include-deps --force ansible-core selinux
```

# Ansible Galaxy Needs
```
ansible-galaxy collection install --upgrade ansible.posix ansible.utils community.general community.libvirt containers.podman
```

# How to upgrade ansible with pipx
```
pipx upgrade-all --include-injected
```

# How to install the ansible dev tools with pipx
```
pipx inject --include-apps ansible-core ansible-dev-tools
```
