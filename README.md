# demo-ansible-docker-image
docker build --tag="gabrielferreira/demo-ansible-docker-image" .
docker run -p 9000:80 --name some-ad-image -it gabrielferreira/demo-ansible-docker-image
