show list of built images \
`docker images`	or \
`docker image ls`

show list of running containers \
`docker ps [-a]`	

build from PATH \
`docker build -t TAG PATH`

run image with port mapping \
`docker run -p LOCAL_PORT:IMAGE_PORT IMAGE_TAG`	

run image if ctrl+C not working \
`docker run -it IMAGE_TAG`	\
`-d` - for detached mode

stop running image \
`docker stop CONTAINER_ID`	

remove image by ID \
`docker rmi IMAGE_ID`	

rename branch tag \
`docker tag OLD_NAME_TAG NEW_NAME_TAG`  	

login to remote docker hub \
`docker login CONTAINER_REGISTRY_URL`	

push container to remote
`docker push CONTAINER_REGISTRY_URL/TAG_NAME`	

save and load docker image as archive \
`docker save [image] -o file.tar`
`docker load -i file.tar`
