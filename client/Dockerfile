FROM node:alpine
WORKDIR /app
COPY ./client ./
RUN chmod 777 node_modules/.bin/react-scripts
RUN npm i
CMD ["npm", "run", "start"]
