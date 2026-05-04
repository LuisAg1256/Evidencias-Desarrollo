# Evidencias-Desarrollo

## Instalacion de CouchDB
Se instalo mediante la terminal de ubuntu con los siguientes comandos:
```PowerShell
sudo apt update && sudo apt install -y curl apt-transport-https gnupg\
```
```PowerShell
curl https://couchdb.apache.org/repo/keys.asc | gpg --dearmor | sudo tee /usr/share/keyrings/couchdb-archive-keyring.gpg >/dev/null
```
```PowerShell
echo "deb [signed-by=/usr/share/keyrings/couchdb-archive-keyring.gpg] https://couchdb.apache.org/repo/debian $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/couchdb.list >/dev/null
```
```PowerShell
sudo apt update
sudo apt install -y couchdb
```
<img width="774" height="497" alt="Screenshot from 2026-05-04 15-27-52" src="https://github.com/user-attachments/assets/1da02dd2-2b11-4d9a-86a5-9faa7819ed8c" />

## Instalacion de docker levantado con couchDB

<img width="774" height="497" alt="Screenshot from 2026-05-04 15-32-02" src="https://github.com/user-attachments/assets/9fc067cd-ca3e-49aa-8f6e-b739f8843478" />
