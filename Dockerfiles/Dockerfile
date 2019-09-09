FROM tomcat

MAINTAINER Devopsuser

COPY WebApp.war /usr/local/tomcat/webapps/WebApp.war

RUN cd /usr/local/tomcat/webapps/

RUN mkdir well-known

RUN cd well-known

RUN mkdir acme-challenge

COPY _iSVqz3LJW-PdIS4WVTE5zXW8e6wdtNk5wgyKGnIqfw /usr/local/tomcat/webapps/.well-known/acme-challenge/_iSVqz3LJW-PdIS4WVTE5zXW8e6wdtNk5wgyKGnIqfw

COPY 9OtwYm96JUm1eZZLD250huHPmXmCPkxaaYN1txJftyQ /usr/local/tomcat/webapps/.well-known/acme-challenge/9OtwYm96JUm1eZZLD250huHPmXmCPkxaaYN1txJftyQ

COPY yMDsZCg5twyxigwpUi1u5JxvDclL8WwgPj8KLYTY1yk /usr/local/tomcat/webapps/.well-known/acme-challenge/yMDsZCg5twyxigwpUi1u5JxvDclL8WwgPj8KLYTY1yk

RUN cd /usr/local/tomcat/webapps/

RUN mv well-known .well-known
