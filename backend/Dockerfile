FROM node:14.21.3-alpine
WORKDIR /app
RUN npm init -y && npm install express mongoose && npm install -g nodemon
COPY . .
EXPOSE 8080
CMD	node index.js
