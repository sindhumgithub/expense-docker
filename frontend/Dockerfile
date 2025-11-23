FROM nginx:1.24
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/conf.d/default.conf
RUN rm -rf /etc/nginx/nginx.conf
#RUN mkdir /etc/nginx/default.d
COPY nginx.conf /etc/nginx/nginx.conf
COPY fixed/ /usr/share/nginx/html/