FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY https://raw.githubusercontent.com/daws-81s/notes/refs/heads/main/session-44.txt  /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]