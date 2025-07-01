# jenkins-custom/Dockerfile
FROM jenkins/jenkins:lts

USER root

# Instala el cliente Docker
RUN apt-get update && \
    apt-get install -y docker.io && \
    rm -rf /var/lib/apt/lists/*

USER jenkins
