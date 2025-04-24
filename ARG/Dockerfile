# FROM almalinux:9
# ENV Course = "Devsecops with AWS"\
#     Trainer = "Shivakumar Reddy"\
#     Containerization ="Docker"\
#     Duration = "120hrs"
# RUN echo "Hello: ${Trainer}" > /tmp/devops.txt
# CMD ["sleep" , "100"]
ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
#here user1 is key, someuser is default value
ARG USERNAME=Sivakumar
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]