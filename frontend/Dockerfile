FROM nginx:1.24
RUN rm -rf /usr/share/nginx/html/*
#RUN rm -rf /etc/nginx/conf.d/default.conf
RUN mkdir /etc/nginx/default.d
COPY expense.conf /etc/nginx/default.d/expense.conf
COPY fixed/ /usr/share/nginx/html/