FROM node:lts-alpine
WORKDIR /usr/src/app
RUN npm install --production --silent && mv node_modules ../
RUN chown -R node /usr/src/app
CMD ["npm", "start"]
