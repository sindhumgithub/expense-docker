FROM nginx:1.24
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY expense.conf /etc/nginx/conf.d/expense.conf
COPY fixed/ /usr/share/nginx/html/