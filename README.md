# ansible-zabbix-agent-centos

ansible role to install zabbix agent on CentOS

https://galaxy.ansible.com/suzuki-shunsuke/zabbix-agent-centos/

## Requirements

Nothing.

## Role Variables

name | required | description
--- | --- | ---
zabbix_full_version | yes | zabbix version

## Dependencies

Nothing.

## Example Playbook

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.zabbix-agent-centos
    zabbix_full_version: 3.2.4-2
    become: yes
```

## License

[MIT](LICENSE)
