FROM node:10

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install
# run nginx -t to check for syntax errors?

COPY . .

EXPOSE 3000 

CMD ["node", "app.js"]