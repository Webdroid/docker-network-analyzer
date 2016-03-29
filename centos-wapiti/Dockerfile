FROM centos:latest

ENV WAPITI_VERSION 2.3.0
ENV LANG en
ENV PATH /opt/wapiti/bin:$PATH

RUN yum -y update && yum -y install epel-release && yum -y install wget python-requests python-beautifulsoup openssl && \
mkdir -p /opt /workdir && \
cd /opt && \
wget http://downloads.sourceforge.net/project/wapiti/wapiti/wapiti-${WAPITI_VERSION}/wapiti-${WAPITI_VERSION}.tar.gz && \
tar xfvz wapiti-${WAPITI_VERSION}.tar.gz && \
rm -fr wapiti-${WAPITI_VERSION}.tar.gz && \
cd wapiti-${WAPITI_VERSION} && \
ln -sF /opt/wapiti-${WAPITI_VERSION} /opt/wapiti && \
chmod 755 /opt/wapiti/bin/wapiti && \
adduser -s /bin/bash wapiti && chown -R wapiti /workdir

USER wapiti

VOLUME /workdir
WORKDIR /workdir

ENTRYPOINT ["wapiti"]

CMD ["--help"]
