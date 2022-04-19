FROM node:alpine
WORKDIR /app
COPY /server/package.json ./
COPY /server/package-lock.json ./
COPY ./server/index.js ./
RUN npm i
CMD ["npm", "run", "start"]
