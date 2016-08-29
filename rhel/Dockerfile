FROM registry.access.redhat.com/rhscl/httpd-24-rhel7
MAINTAINER Samuel Tauil stauil@redhat.com
RUN mkdir -p /opt/rh/httpd24/root/var/www/html
VOLUME /opt/rh/httpd24/root/var/www/html
WORKDIR /opt/rh/httpd24/root/var/www/html
COPY index.html .
USER 1001
EXPOSE 80
