FROM almalinux:9 
RUN dnf install nginx -y
# to remove existing html file2
RUN rm -f /usr/share/nginx/html/index.html
# this executes when someone uses or image as their base OS
ONBUILD  COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]