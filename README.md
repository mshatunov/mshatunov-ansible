# mshatunov-ansible

## run nginx
```ansible-playbook --ask-vault-pass nginx.yml -i inventory```

## manual update letcencrypt certs
sudo add-apt-repository ppa:certbot/certbot
sudo apt-get update
sudo apt-get install certbot
sudo certbot certonly
sudo cat /etc/letsencrypt/live/<domen>/