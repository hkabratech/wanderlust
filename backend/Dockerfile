FROM node:23

WORKDIR /app

COPY . .

RUN npm i

COPY .env.sample .env

EXPOSE 5000

CMD ["npm", "start"]