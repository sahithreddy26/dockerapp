FROM node:alpine
WORKDIR /app
COPY /client/package.json ./
COPY /client/package-lock.json ./
COPY ./ ./
RUN npm i
CMD ["npm", "run", "start"]
