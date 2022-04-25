FROM  node:14-alpine AS todobackend
WORKDIR /todo-app
COPY package*.json ./
COPY . .
EXPOSE 3001
RUN npm install
ADD node_modules.tar.gz .