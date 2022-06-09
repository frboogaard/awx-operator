FROM quay.io/ansible/awx-ee:latest

USER root
RUN yum install nmap -y && yum clean all -y && rm -rf /var/cache/yum

USER 1000
