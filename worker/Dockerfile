FROM node:alpine
WORKDIR "/app"
RUN npm i -g nodemon
COPY ./package.json .
RUN npm install
COPY . .
CMD ["npm", "run", "start"]