FROM node:20-alpine

WORKDIR /app

# Install nodemon globally for dev script support
RUN npm install -g nodemon

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "run", "dev"]
