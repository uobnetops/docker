FROM centos:7
LABEL maintainer="Jonathan Gazeley <jonathan.gazeley@bristol.ac.uk>"

RUN rpm -ivh http://yum.puppetlabs.com/puppetlabs-release-pc1-el-7.noarch.rpm \
    && rpm -ivh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm \
    && yum -y update \
    && yum -y install ruby puppet-agent which findutils ShellCheck \
    && gem install puppet-lint
