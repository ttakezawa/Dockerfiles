# Docker Version: 0.6.7

FROM centos

RUN yum install -y openssh-server openssh-clients
RUN sed -i.bak -r 's/^UsePAM yes$/UsePAM no/' /etc/ssh/sshd_config
RUN echo root:root | chpasswd
