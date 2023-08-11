# Dicetask2
sudo docker run -it -d --name -p 80:80 ubuntu (p publish , 1st 80 host , 2nd 80 container)
#check Images
sudo docker images

#Check status
sudo systemctl status docker
#Start Docker
sudo systemctl start docker

#Stop Docker
sudo systemctl stop docker

#Check Version
sudo docker -v

#Docker Run
sudo docker run -it -d ubuntu
sudo docker run -it -d --name ubuntu
sudo docker run -it -d --ibrar -p 80:80 ubuntu (p publish , 1st 80 host , 2nd 80 container)


#Check Docke process
sudo docker ps -a
sudo docker ps 

#Container stop start restart remove and kill
sudo docker restart name/id
sudo docker stop name/id
sudo docker start name/id
sudo docker rmi name/id
sudo docker rm name/id
sudo docker kill name/id

#Inter in container
sudo docker exec -ti ibrar bash
#Inter in container
sudo docker exec -ti ibrar bash
