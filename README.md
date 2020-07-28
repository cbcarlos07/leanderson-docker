# Instalar no Mint

Para instalar no Mint

1. sudo apt-get remove docker docker-engine docker.io

2. sudo apt-get update

3. sudo apt-get install apt-transport-https ca-certificates curl software-properties-common

4. curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

5. sudo apt-key fingerprint 0EBFCD88

6. sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(. /etc/os-release; echo "$UBUNTU_CODENAME") stable"

7. sudo apt-get update

8. sudo apt-get install docker-ce

9. sudo usermod -aG docker $USER // It is need restart System# leanderson-docker
