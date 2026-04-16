# ansible-zabbix

**Deploy Agent**
```
ansible-playbook -i hosts -l < optional if not targeting specific host > deploy-agent.yml -b -K
```


**Add Host**
```
ansible-playbook -i hosts -l < optional if not targeting specific host > add-hosts.yml -K -J
```
