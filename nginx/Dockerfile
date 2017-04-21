From nginx:latest
RUN  apt-get update && apt-get install -y net-tools
COPY conf/ /etc/nginx/
ADD default_conf/ /etc/nginx/conf.d/
ADD project/ /usr/share/nginx/html/
