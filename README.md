v2-plugin TLS


ENV  Debian 10

ddns add

ddns.sh


install Docker  

apt update && apt install curl

curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun

docker pull acrisliu/shadowsocks-libev

docker run.yml

###stop＆restart docker###

debian

docker stop ID

docker container rm $(docker container ps -aq)

centos 7

docker stop $(docker ps -a -q)

docker rm $(docker ps -a -q)

systemctl start docker

sudo systemctl enable docker



run BBR plus

wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh





