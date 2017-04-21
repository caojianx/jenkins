From nginx:latest
RUN  apt-get update \
     apt-get install net-tools \
     apt-get -y install netstat
COPY conf/ /etc/nginx/
ADD default_conf/ /etc/nginx/conf.d/
ADD project/ /usr/share/nginx/html/
