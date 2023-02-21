FROM node:14.15.4
WORKDIR /app
COPY package*.json /app/
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "app.js"]