FROM centos:latest

RUN yum -y update && yum -y install epel-release && yum -y install nmap

RUN mkdir /devlab
VOLUME ["/devlab"]
WORKDIR /devlab

ENTRYPOINT ["nmap"]
