# Docker-install-redhat

yum install docker

yum remove docker docker-common docker-selinux docker-engine

yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo

yum install docker-ce

systemctl status docker

systemctl start docker

systemctl stop docker


