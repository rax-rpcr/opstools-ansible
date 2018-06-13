FROM centos:7

MAINTAINER RPC-R Team <brewmasters@rackspace.com>

ADD sensu.repo /etc/yum.repos.d/
RUN yum install -y sensu

EXPOSE 4567

ENTRYPOINT ["/opt/sensu/bin/sensu-service"]
