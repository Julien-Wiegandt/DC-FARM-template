FROM node

WORKDIR /usr/src/app/react-app

COPY package*.json ./

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]