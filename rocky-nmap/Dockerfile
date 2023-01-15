FROM rockylinux:9-minimal
MAINTAINER Webdroid

RUN dnf -y update \
&& dnf -y install nmap \
&& dnf clean all \
&& mkdir /workdir

VOLUME /workdir
WORKDIR /workdir

ENTRYPOINT ["nmap"]