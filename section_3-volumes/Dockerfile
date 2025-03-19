FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT 80

EXPOSE $DEFAULT_PORT

ARG DEFAULT_PORT=80

# VOLUME [ "/app/node_modules" ]

VOLUME ["/temp"]

CMD [ "npm", "start" ]