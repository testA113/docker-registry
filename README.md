# docker-registry
a quick test for creating a container registry with auth

# How to start

    cd data 
    docker-compose up

credentials are:

    admin
    asdfasdf

# How to use

    docker tag anImageIHave:latest localhost:5005/registryImage:latest
    docker push localhost:5005/registryImage:latest
    docker pull localhost:5005/registryImage:latest

# How to change credentials

    cd auth 
    rm registry.password 
    htpasswd -Bc registry.password somenewuser
