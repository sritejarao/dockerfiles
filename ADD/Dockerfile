FROM almalinux:9 
RUN dnf install nginx -y
# to remove existing html file
RUN rm -f /usr/share/nginx/html/index.html
ADD https://www.biggbossteluguvoteonline.in/2024/09/vishnupriya.html /usr/share/nginx/html/index.html
RUN chmod +xr /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/ #tar untar
CMD ["nginx", "-g", "daemon off;"]