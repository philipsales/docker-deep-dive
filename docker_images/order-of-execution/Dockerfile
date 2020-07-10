FROM centos:latest 
RUN mkdir -p ~/new-dir1
RUN useradd -ms /bin/bash cloud_user
RUN mkdir -p /etc/myconf
RUN echo "some config" >> /etc/myconf/my.conf
#NOTE that USER is like sudo su - cloud_user
USER cloud_user
RUN mkdir -p ~/new-dir2
