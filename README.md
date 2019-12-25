# HashiCorp-Vault
## Installation Steps
wget https://releases.hashicorp.com/vault/1.0.3/vault_1.0.3_linux_amd64.zip

unzip vault_1.0.3_linux_amd64.zip -d .

sudo cp vault /usr/bin/

sudo mkdir /etc/vault

sudo mkdir /opt/vault-data

sudo mkdir -p /logs/vault/

sudo vi /etc/vault/config.json

sudo vi /etc/systemd/system/vault.service

sudo systemctl start vault.service

sudo systemctl status vault.service
