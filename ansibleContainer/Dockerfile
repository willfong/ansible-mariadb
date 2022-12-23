FROM rockylinux:9
RUN yum update -y && yum install -y epel-release && yum install -y ansible python3-mysqlclient
WORKDIR /playbooks
CMD ["tail", "-f", "/dev/null"]