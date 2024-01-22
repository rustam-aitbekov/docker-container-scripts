# docker-container-scripts

docker-compose up -d

docker-compose down

--rmi local to delete images
-v to remove volumes

#Generate sha256 sum
echo -n 'password' | sha256sum | awk '{ print $1 }' //password must be min 32 character long