FROM node

RUN mkdir -p /var/node
RUN mkdir -p /var/test
ADD content-express-demo-app/ /var/node/
WORKDIR /var/node
RUN npm install
CMD ./bin/www
