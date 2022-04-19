FROM node:alpine
WORKDIR /app
COPY ./client ./
RUN sudo chmod +x node_modules/.bin/react-scripts
RUN npm i
CMD ["npm", "run", "start"]
