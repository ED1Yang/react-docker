FROM nginx
RUN apt-get update
RUN apt-get install -y vim
RUN rm /etc/nginx/conf.d/default.conf 
COPY ./default.conf /etc/nginx/conf.d

