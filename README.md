# Requirement  

- maas-cli installed in root
- .pems/ in home folder with required keys

# How to run

```
ansible-playbook pb-list-inv.yml --extra-vars 'cfg_var=config_stg_test'
```

```cfg_var``` is a config file located in in vars/ sub-folder which can be customized to target specific cloud and specific region.