Done using 

#To create our Dockerfile
touch Dockerfile

#to edit what we need to build an image
nano Dockerfile

#To build the dockerfile
docker build .


#To get the image id
docker images

#to run our docker application
docker run --name test sha256:d720060a80a3653cb9e7b2e376394196defca3419c6403f3e9e642d5a40d7fb7



#to commit
docker ps -a

#docker login to push
docker login -u mikehj24 -p yourpasswordhere docker.io
 
# create this repo @hub.docker.com
docker tag sbakuber/sbakubernetes:2 mikehj24/sba
 
docker push mikehj24/sba
#refresh dockerhub page for newly created image
