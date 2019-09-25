FROM ubuntu:18.04

RUN apt update -y
RUN apt install software-properties-common -y
RUN apt-add-repository ppa:ansible/ansible -y
RUN sudo apt update -y 
RUN apt install ansible
RUN mkdir /etc/ansible/