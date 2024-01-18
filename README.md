# docker-container-scripts

docker-compose -f <file-name>.yml up -d

docker-compose -f <file-name>.yml down


echo -n 'password' | sha256sum | awk '{ print $1 }' //password must be min 32 character long