FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=f2hard3
ENV MONGODB_PASSWORD=AiUXfsKJm4cxKad8
ENV MONGODB_URL=cluster0.gc1oxau.mongodb.net
ENV MONGODB_NAME=goals-dev

CMD ["npm", "start"]