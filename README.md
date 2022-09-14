# docker

# автоматическая установка docker + docker-compose 

```
. <(wget -qO- https://raw.githubusercontent.com/95brsu/docker/main/install.sh) 
```
# проверить версию 
```
docker --version 

docker-compose --version
```
# ручная установка docker 
```
apt update
apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
apt update
apt-cache policy docker-ce
sudo apt install docker-ce
systemctl status docker
```
# проверить версию
```
docker --version
```
# ручная установка docker-compose 

### проверяем версию https://github.com/docker/compose/releases и подставляем в команду установки
```
curl -L "https://github.com/docker/compose/releases/download/v2.10.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```
# проверить версию
```
docker-compose --version
```
