
Installation on Ubuntu 18.04:

```bash
sudo apt install curl

curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh -o install_nvm.sh
bash install_nvm.sh
source ~/.profile
nvm install 12.14.1

npm install -g typescript
npm install
npm build
```
