FROM node:fermium-stretch
WORKDIR /app
COPY package.json .
RUN npm install
COPY index.js .
ENTRYPOINT ["node", "index.js"]
EXPOSE 3000
