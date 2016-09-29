#PVS-Docker
This is a docker container for the verification system PVS (http://pvs.csl.sri.com/)

To run it, you should do :

```
docker build -t pvs-container .
docker run -v `pwd`:/home/work -it pvs-container bin/bash
```

It is also on Dockerhub so you can simply do : 

```
docker run -v `pwd`:/home/work -it prygan/pvs-docker bin/bash
```

To run PVS, just type : 
```
pvs
```

