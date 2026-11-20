FROM node:24
WORKDIR /app
COPY package.json .
COPY *.js .
ENV MONGO="true" \
    MONGO_URL="mongodb://mongodb:27017/catalogue"
RUN npm install
CMD ["node", "server.js"]