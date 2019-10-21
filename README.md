# DockerExercise1
### command Lines
```
sudo docker images
sudo docker ps -a
```
#### To remove container
```
sudo docker rm -f //containerId//
```
### To remove Images
```
sudo docker rmi -f //imageName//
```
### To create image 
```
sudo docker build -t //imageName// .
```
### To create container
```
sudo docker run -d --name //containerName// --network=host //mongo//
```
### To root mode inside container
```
sudo docker exec -it //containerName// bash
```
