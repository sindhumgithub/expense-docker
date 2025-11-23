FROM node:22.21
RUN useradd --system --home /opt/backend/ --shell /sbin/nologin --comment "roboshop system user" expense
USER expense
WORKDIR /opt/backend/
COPY expense/ /opt/backend/
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]
