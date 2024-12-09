INSTALAÇÃO DO QBITTORRENT-NOX COM DOCKER COMPOSE:

apt update && apt upgrade -y
apt install -y git curl apt-transport-https ca-certificates software-properties-common

apt install git

git clone https://github.com/shazaltman/qbittorrent-nox.git

cd qbittorrent-nox

chmod +x install

./install

ip a
