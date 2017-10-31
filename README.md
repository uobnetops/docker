# Docker

This repo contains `Dockerfile`s for custom Docker images that are used by the
NetOps team at the University of Bristol.

## Images

### `netops-build`

Image specifically for the purpose of building RPMs. Based on CentOS 7.
Image publicly available on
[Docker Hub](https://hub.docker.com/r/universityofbristol/netops-build/).

### `netops-ci`

Image specifically for the purpose of running CI tests against the Puppet
control repo. Based on CentOS 7. Image publicly available on
[Docker Hub](https://hub.docker.com/r/universityofbristol/netops-ci/).

### `netops-shellcheck`

Image specifically for running ShellCheck against shell scripts. Based on Fedora
(latest) as the version of ShellCheck in CentOS 7 is too old. Image publicly available on
[Docker Hub](https://hub.docker.com/r/universityofbristol/netops-shellcheck/).
