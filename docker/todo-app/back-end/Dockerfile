FROM  node:14-alpine AS todobackend
WORKDIR /todo-app/back-end
COPY package*.json ./
COPY . .
EXPOSE 3001
RUN npm install
ADD node_modules.tar.gz .
CMD ["npm", "start"]