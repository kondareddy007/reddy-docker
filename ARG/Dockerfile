ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG COURSE 
ARG TRAINER 
RUN echo "course is:${COURSE}, trainer is:${TRAINER}"
ENV course=${COURSE}
ENV trainer=${TRAINER}
CMD [ "sleep", "100" ]





# ARG vs ENV
# -----------------
# ARG instruction can provide values to the Dockerfile only at buildtime. ENV variables have access in the container

# How can I use ARG variables inside container?
# Assign the values of ARG to ENV variables so that you can access them inside container as well

# ARG instruction can be used before FROM instruction to provide values to FROM instruction.

# ARG value deffnied before FROM will not be accessed after FROM
#if you not pass the ARGUMENTS at build time below error will come.
#docker: Error response from daemon: unable to find user adduser : no matching entries in passwd file.
#docker build -t arg:v1 . --build-arg username=cherry
#docker run -d arg:v1 
#docker exec -it 0a4f90e38b bash
