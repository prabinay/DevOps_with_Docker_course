#run alpine container
docker run -it  devopsdockeruh/simple-web-service:alpine

#start by its container ID
docker start 78f1f08aa419

#see size of each running containers
docker ps --size

Output:
CONTAINER ID        IMAGE                                      COMMAND
    CREATED             STATUS              PORTS               NAMES
 SIZE
78f1f08aa419        devopsdockeruh/simple-web-service:alpine   "/usr/src/app/server"   20 minutes ago      Up 20 minutes                           nervous_lamport     28.5 kB (virtual 15.7 MB)
0ba6e15ba63d        4e3362e907d5                               "/usr/src/app/server"   About an hour ago   Up About an hour                        angry_nightingale   58.9 MB (virtual 142 MB)
9
