# This is the docker container for PVS a tool used by "Les Mines de Nantes"

To run it, you should do that:

```
docker build -t pvs-container .
docker run -v `pwd`:/home/work -it pvs-container bin/bash
```
