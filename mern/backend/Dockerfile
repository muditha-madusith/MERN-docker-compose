FROM node:18.9.1

WORKDIR /app

COPY package.json .

RUN npm install --force

COPY . .

EXPOSE 5050

CMD [ "npm", "start" ]