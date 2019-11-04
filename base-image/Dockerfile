FROM centos/python-36-centos7

USER root
RUN yum -y install graphviz* &&\
    yum clean all
USER 1001

RUN fix-permissions /opt/app-root