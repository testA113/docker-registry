# docker-registry
a quick test for creating a container registry with auth

# How to use
```cd data```\n
```docker-compose up```
credentials are:
admin
asdfasdf

# How to change credentials
```cd auth```\n
```rm registry.password```\n
```htpasswd -Bc registry.password somenewuser```
