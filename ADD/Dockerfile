FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/Bhargavi-P2/shell-practice/blob/main/06-array.sh /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]