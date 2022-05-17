FROM node:14-alpine

WORKDIR '/app'

COPY package.json .
RUN rm -rf node_modules && npm install
COPY . .

CMD ["npm", "start"]