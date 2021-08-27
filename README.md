# AI Tester
## _The Best AI Framework script, Ever_

[![Tensorflow Keras](https://pic4.zhimg.com/80/v2-b9909815be5a652ab6d79761dd8c21d3_720w.jpg)](https://zhuanlan.zhihu.com/p/89017996)

Powered by [![Docker](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQjePG-OsC4pSv5y3aYS-1J1uHOOno7jIKlPcbxoYTkDkVQuukm6zVQYizi6sUwv5yiPpM&usqp=CAU)](https://docs.docker.com/)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://hub.docker.com/repository/docker/105552010/tensorflow)

AI Tester is a cloud-enabled, containerized, offline-storage compatible,
it could help you to test GPU by BIG MODEL for pressure testing, efficiency testing would also be available.

- Check out tf1 and tf2 folder
- Run the python script
- ✨Enjoy!✨

## Features

- Pressure Test
- Efficiency Test
- Support Tensorflow1,2 and Keras
- Support Python3.6+(Recommend 3.8)
- Support Nvidia GPU

## Version List

| Item | Tensorflow | Keras | Cuda | Cudnn | Script |
| ---- | ---------- | ----- | ---- | ----- | ------ |
| version 1 | 2.6.0 | 2.6.0 | 11.2 | 8 | tf2 |
| version 2 | 1.15 | 2.3.1 | 10.0 | 7 | tf1 |

## Installation

AI Tester requires [Docker](https://docs.docker.com/get-docker/) to run.

Install the dependencies and devDependencies and start the server.

```sh
sudo apt-get update
sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo apt-key fingerprint 0EBFCD88
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt-get update
sudo apt-cache madison docker-ce
sudo apt-get install docker-ce=19.03.6~ce-0~ubuntu-xenial
```

## Docker

Download Image

For Tensorflow 1.15
```sh
sudo docker pull 105552010/tensorflow:v1.15.5
```
For Tensorflow 2.6
```sh
sudo docker pull 105552010/tensorflow:v2.6.0
```

Start Container...

```sh
sudo docker run --name=test -it 105552010/tensorflow:v2.6.0 /bin/bash
```
You can find the scripts inside tf folder...

## How to support
ETH-ERC20: 0xbf87fbd717d8bd90019cfe7b05b1802229b302dd

## License

MIT
