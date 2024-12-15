FROM almalinux:8
#RUN cd /tmp
WORKDIR /tmp
RUN echo "hello reddy" > hello.txt
CMD [ "sleep", "100" ]


#if you use RUN the hello,txt file is not available in /tmp folder. it is avalibale in /home folder.
#if you us ethe WORKDIR the helow.txt file available in /tmp file only.
