# https://hub.docker.com/_/clearlinux
FROM clearlinux:latest
LABEL org.opencontainers.image.authors="githubfoam"

# https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-clear-linux
RUN swupd bundle-add sysadmin-hostmgmt && \
    swupd update && ansible --version

WORKDIR /tmp