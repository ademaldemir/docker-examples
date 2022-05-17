FROM node:16-alpine

WORKDIR /app

COPY /app/package.json .

RUN npm install

COPY /app .

EXPOSE 4000
# required for docker desktop port mapping

CMD ["node", "app.js"]