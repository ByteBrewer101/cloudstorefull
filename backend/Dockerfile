FROM node:16
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
VOLUME /app/files
EXPOSE 5000
CMD ["node", "index.js"]
