FROM node:fermium
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
CMD ["node", "index.js"]