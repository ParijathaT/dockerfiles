# FROM almalinux:9
# RUN useradd expense #giving root access and install git or anything into container 
# CMD ["sleep" , "100"]
# removing user from docker and give normal access to user
FROM almalinux:9
RUN useradd expense
USER expense
CMD ["sleep" , "100"]