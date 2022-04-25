FROM  node:14-alpine AS todofrontend
WORKDIR /todo-app/front-end/
COPY package*.json ./
COPY . .
EXPOSE 3000
RUN npm install
ADD node_modules.tar.gz .
CMD ["npm", "start"]