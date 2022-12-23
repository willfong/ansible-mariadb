FROM rockylinux:9
RUN yum update -y && yum install -y epel-release && yum install -y ansible
WORKDIR /playbooks
CMD ["tail", "-f", "/dev/null"]