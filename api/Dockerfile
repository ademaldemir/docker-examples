FROM node:16-alpine

WORKDIR /app

COPY /app .

RUN npm install

EXPOSE 4000
# required for docker desktop port mapping

CMD ["node", "app.js"]