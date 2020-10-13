FROM nginx
COPY nginx.conf /etc/nginx/nginx.conf
COPY web.conf /etc/nginx/conf.d/web.conf
VOLUME /Users/idark/Desktop/src/docker/study/docker_study/Dockerfile/web /usr/share/nginx/html
RUN rm -rf /etc/nginx/conf.d/default.conf
EXPOSE 80
ENTRYPOINT nginx -g "daemon off;"