# Mechline

## Staging

Check if environment is ready
```
ansible -i hosts -m ping staging
```

Deploy latest version of wordpress
```
ansible-playbook -i hosts -l staging deploy.yml 
```


## Production