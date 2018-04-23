# study-docker

## docker version
sudo docker version
Client:
 Version:      1.13.1
 API version:  1.26
 Go version:   go1.8.3
 Git commit:   092cba3
 Built:        Thu Oct 12 22:34:44 2017
 OS/Arch:      linux/amd64

Server:
 Version:      1.13.1
 API version:  1.26 (minimum version 1.12)
 Go version:   go1.8.3
 Git commit:   092cba3
 Built:        Thu Oct 12 22:34:44 2017
 OS/Arch:      linux/amd64
 Experimental: false

## Component

Docker Engine
Docker Registry
Docker Compose
Docker Machine
Docker Swarm

## Core

namespace ... コンテナを区画化する仕組み
cgroups ... プロセス・スレッドをグループ化して、そのグループ内に存在するプロセス・スレッドに対して管理を行うための機能

## Network

Dockerインストール -> サーバの物理NIC(echo0)が仮想ブリッジ(docker0 = Docker起動後にデフォルトで作成される)に接続

## COMMAND LIST
sudo docker image pull rabbitmq:3.7.4-alpine
sudo docker image ls

