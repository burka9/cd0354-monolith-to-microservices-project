FROM node:12
# create app directory
WORKDIR /usr/src/app
# install dependencies
COPY package*.json ./
RUN npm ci
COPY . .
EXPOSE 8080
CMD ["npm", "run", "dev"]