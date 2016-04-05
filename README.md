# demo-ansible-docker-image
First you need to clone the project
```sh
$ git clone git@github.com:gabrielferreira/demo-ansible-docker-image.git
$ cd demo-ansible-docker-image
```
execute the command bellow to build the Docker Image
```sh
$ docker build --tag="gabrielferreira/demo-ansible-docker-image" .
```
execute the command bellow to run the Docker
```sh
$ docker run -p 9000:80 --name some-ad-image -it gabrielferreira/demo-ansible-docker-image
```

Now open your browser and enter the Docker URL **http://<DOCKER_URL>:9000**

**It's Done**
