FROM almalinux:9
RUN dnf install nginx -y
RUN systemctl start nginx
RUN systemctl enable nginx
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
