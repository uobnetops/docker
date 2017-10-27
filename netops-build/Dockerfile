FROM centos:7
LABEL maintainer="Jonathan Gazeley <jonathan.gazeley@bristol.ac.uk>"

RUN rpm -ivh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm \
    && yum clean metadata \
    && yum -y update \
    && yum -y install \
      autoconf \
      automake \
      binutils \
      bison \
      flex \
      gcc \
      gcc-c++ \
      gettext \
      libtool \
      make \
      patch \
      pkgconfig \
      redhat-rpm-config \
      rpm-build \
      byacc \
      cscope \
      ctags \
      diffstat \
      doxygen \
      elfutils \
      gcc-gfortran \
      indent \
      intltool \
      patchutils \
      rcs \
      swig \
      systemtap \
      rubygem-gem2rpm \
      libnl-devel \
      openssl-devel \
      readline-devel \
      dbus-devel \
      rpmdevtools \
      nagios-plugins-perl \
    && yum clean all \
    && rm -rf /var/cache/yum \
