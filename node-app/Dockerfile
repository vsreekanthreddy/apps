FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "index.js"]


#docker build -t node-docker-app .
#docker run -p 3000:3000 node-docker-app
