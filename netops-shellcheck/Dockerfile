FROM fedora:latest
LABEL maintainer="Jonathan Gazeley <jonathan.gazeley@bristol.ac.uk>"

RUN yum -y update \
    && yum -y --enablerepo=updates install findutils ShellCheck \
    && yum clean all \
    && rm -rf /var/cache/yum
