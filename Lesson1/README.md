# 初めてのDocker

## Dockerのバージョン確認
```
docker --version
Docker version 28.1.1, build 4eba377
docker -v
Docker version 28.1.1, build 4eba377
```
dockerのバージョン確認と環境構築の確認に使われている

## HelloWorld
```
docker container run hello-world
```
DockerのHelloWorld
今回は旧コマンドの`docker run`ではなく`docker container run`を使用した。
新コマンドのほうが学習に際し混乱が減らせると考えた。

## Dockerのサブコマンド
```
docker
docker container
docker image
docker network
docker volume
```
これらに`ls`や`run`などそれぞれに配置されたコマンドを続けることでコマンドが完成する

個人的にはDockerのコマンドを効率的に覚えるために旧コマンドの使用は慣れるまで控えたい。