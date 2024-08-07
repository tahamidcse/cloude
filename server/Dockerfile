
FROM node:20
WORKDIR /usr/src/codap
COPY package*.json ./

RUN npm install
COPY . .

EXPOSE 9000

CMD ["npm", "run","dev"]
