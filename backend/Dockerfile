FROM node:14
WORKDIR /backend
COPY package.json /backend
RUN npm install
COPY . /backend
EXPOSE 2000
CMD ["node", "server.js"]