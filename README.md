# PVS-Docker
This is a docker container for the verification system PVS (http://pvs.csl.sri.com/)

## Manual build

```
$ docker build -t pvs-container .
$ docker run -v `pwd`:/home/work -it pvs-container
```

## Use via docker hub

### Launch bash shell

```
$ docker run -v `pwd`:/home/work -it prygan/pvs-docker
```

To run PVS, just type : 
```
$ pvs
```

### Launch PVS 

```
$ docker run -v `pwd`:/home/work -it prygan/pvs-docker /pvs/pvs
```