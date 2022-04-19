FROM node:alpine
WORKDIR /app
COPY /client/package.json ./
COPY /client/package-lock.json ./
COPY ./client/src ./
COPY ./client/public ./
COPY ./client/node_modules ./
RUN npm i
CMD ["npm", "run", "start"]
