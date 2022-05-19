FROM node:14.19.2-stretch
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
CMD ["node", "index.js"]