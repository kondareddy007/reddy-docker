FROM almalinux:8
RUN yum install nginx -y
ENV Trainer="Siva" \
    Course="Devops" \
    Duration="120HRS" 
CMD ["nginx","-g","daemon off"]


#We can use ENV varaibe in docker container.
#docker build -t env:v1 .
#docker images
#