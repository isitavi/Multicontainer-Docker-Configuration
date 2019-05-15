# Multicontainer-Docker-Configuration-Example
name: whatever you want to use


image: use your published dockerhub image or any public images from docker hub


hostname: identical to with you services name in docker-compose.yml. By this hostname other containers will be connect to this container.


essential: true or false. if any container essential value is true then if this container fails then other containers will be in a fail state. But at least one container must be in true state in your multi docker configuration file.


Documentation: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_v2config.html#docker-multicontainer-dockerrun-privaterepo


