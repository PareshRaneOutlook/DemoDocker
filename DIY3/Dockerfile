FROM fedora:latest

RUN dnf -y install httpd

ADD webserver.tar.gz /var/www/html/

CMD ["-D", "FOREGROUND"]

ENTRYPOINT [ "/usr/sbin/httpd" ]

EXPOSE 80