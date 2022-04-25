FROM  mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /todo-app/tests
COPY package*.json ./
COPY . .
RUN npm install
ADD node_modules.tar.gz .
CMD ["npm", "test"]