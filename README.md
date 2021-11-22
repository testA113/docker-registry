# docker-registry
a quick test for creating a container registry with auth

# How to use
```cd data && docker-compose up```
credentials are:
admin
asdfasdf

# How to change credentials
```cd auth && rm registry.password && htpasswd -Bc registry.password somenewuser
