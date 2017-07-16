# Propósito
Gerar configuração automática para instalação do notebook dos meninos.

# Para rodar da primeira vez
```
ansible-playbook --ask-pass --ask-sudo-pass --inventory-file=./hostsInicial configurarInicial.yml
```

# Para configurar
```
ansible-playbook --inventory-file=./hosts configurar.yml
```
