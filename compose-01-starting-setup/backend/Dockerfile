FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=amogh
ENV MONGODB_PASSWORD=amogh

CMD ["npm", "start"]