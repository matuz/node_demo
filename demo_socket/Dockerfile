FROM node:6.5.0-slim

WORKDIR /root

COPY pckage.json /root/package.json
RUN npm install

COPY .:/root

CMD ["npm", "start"]
.
