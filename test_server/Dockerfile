FROM centos
RUN yum install git -y
RUN yum install httpd -y
RUN git clone https://github.com/pewxh/testpage /var/www/html/
EXPOSE 80
ENTRYPOINT [ "/usr/sbin/httpd" ]
CMD [ "-D" , "FOREGROUND"]
