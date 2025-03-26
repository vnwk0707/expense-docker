FROM node:20
WORKDIR /opt/backend
COPY package.json .
copy *.js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]