### First, download the roles
```
        ansible-galaxy install -r requirements.yml -p roles

```
### Launching the ansible playbook
```
        ansible-playbook -i inventory/prod.yml site.yml 
```

Ссылка lighthouse-role [https://github.com/gilyazov-ranel/lighthouse-role]
Ссылка vector-role [https://github.com/gilyazov-ranel/vector-role]
