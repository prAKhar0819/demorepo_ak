# pull base image from dockerhub if not exist in local registry 
FROM helloimg
# copy code from local to img
# COPY  <source>   <destination>
COPY count.c /
# run any commmand in shell 
# RUN <command>
RUN gcc -o count /count.c
# run command when conatiner is creating (dedicated task)
CMD ["/count"]
