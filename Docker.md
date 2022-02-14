show list of built images \
`docker images`	

show list of running containers \
`docker ps [-a]`	

build from PATH \
`docker build -t TAG PATH`	

run image with port mapping \
`docker run -p LOCAL_PORT:IMAGE_PORT IMAGE_TAG`	

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
