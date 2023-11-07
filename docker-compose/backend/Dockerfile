FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=mongo
ENV MONGODB_PASSWORD=mongo

CMD ["npm", "start"]