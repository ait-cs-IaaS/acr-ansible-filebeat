# Ansible-Role: acr-ansible-filebeat

AIT-CyberRange: Installs and configures filebeat in the AIT CyberRange. 


## Requirements

- Debian or Ubuntu

## Role Variables

```yaml
filebeat_version: 9.0.2
filebeat_modules: []
filebeat_inputs: []
filebeat_output_conf: {}

filebeat_setup_conf:
    setup.kibana:

filebeat_processors: []

filebeat_ilm_policy_max_age: '1d'
filebeat_ilm_policy_max_size: '25gb'
filebeat_ilm_policy_delete: true
filebeat_ilm_policy_delete_min_age: '5d'
```

## License

GPL-3.0

## Author

- Lenhard Reuter