# Datagram-Network
Setup Datagram Network run with CLI

## Install Dependencies
```
sudo apt update && sudo apt upgrade -y
sudo apt install wget curl screen -y
```
## Download Datagram CLI
```
wget https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux
```
## Check file 
```
ls -l datagram-cli-x86_64-linux
```
## Chmod file 
```
sudo mkdir -p /usr/local/bin
sudo mv datagram-cli-x86_64-linux /usr/local/bin/datagram-cli
sudo chmod +x /usr/local/bin/datagram-cli
```
## Create Screen
```
screen -S datagram
```
## Run CLI
``` bash
datagram-cli run -- -key YOUR_API_KEY
#Change your APIKEY from Datagramnetwork
```
