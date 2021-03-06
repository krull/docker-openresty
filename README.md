# docker-openresty
`docker-openresty` is a Debian based docker image for [OpenResty](https://github.com/openresty)

## Description
I saw that `openresty` has a [docker initiative](https://github.com/openresty/docker-openresty) over at their github project page, but what was missing were Debian Images. Here you will find both `jessie` and `wheezy` build flavors.

For the automated builds go to [hub.docker.com](https://hub.docker.com/r/mcroth/docker-openresty/).

You can use these images directly from [hub.docker.com](https://hub.docker.com/r/mcroth/docker-openresty/) by issuing the following docker commands:
```
docker pull mcroth/docker-openresty:jessie
```
```
docker pull mcroth/docker-openresty:wheezy
```

UPDATE: [openresty/docker-openresty](https://github.com/openresty/docker-openresty/issues/21) added `jessie` and `wheezy` official builds. I will leave this here for historical reason. Thanks @neomantra for the mention!
