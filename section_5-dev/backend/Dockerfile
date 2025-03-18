FROM node:16.20.0

WORKDIR /app

COPY package.json .  

RUN npm install

COPY . .

EXPOSE 80

ENV MONGO_USER=dudedude
ENV MONGO_PASS=secret

CMD ["npm", "start"]

