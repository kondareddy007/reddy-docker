FROM almalinux:8
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/kondareddy007/siva-daws-76s-notes/refs/heads/master/finalsession.txt /tmp
CMD ["nginx","-g","daemon off;"]


#COPY- Copy is used to copy the files from local to image.
#ADD--> Add also used copy the file from remote to images. ADD has two extra capabilities
#1) It can directly download files from internet
#2. It can directly untar the tar or zar files..
#docker build -t add:v1 .
#docker images
#docker run -d -p 80:80 add:v1
#http://44.220.161.238:80
#docker exec -it <Conatiner ID> /bin/bash
