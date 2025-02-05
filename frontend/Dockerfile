# node jave script runtime that makes the front end work
# how to build a node.js docker file for frontend

FROM node:18

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

#RUN npm run build

EXPOSE 5173

CMD ["npm", "run", "dev"]