FROM node:16

COPY . /app
RUN cd /app && npm install

WORKDIR /app

CMD ["/usr/local/bin/node", "/app/app.js"]
