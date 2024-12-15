FROM almalinux:8
ARG username
RUN adduser 
USER $username

CMD [ "sleep", "100" ]





# ARG vs ENV
# -----------------
# ARG instruction can provide values to the Dockerfile only at buildtime. ENV variables have access in the container

# How can I use ARG variables inside container?
# Assign the values of ARG to ENV variables so that you can access them inside container as well

# ARG instruction can be used before FROM instruction to provide values to FROM instruction.

# ARG value deffnied before FROM will not be accessed after FROM
#if you not pass the ARGUMENTS at run time below error will come.
#docker: Error response from daemon: unable to find user adduser : no matching entries in passwd file.