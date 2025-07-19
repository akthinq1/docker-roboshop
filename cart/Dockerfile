FROM node:20
COPY package.json .
COPY *.js .
RUN npm install
ENV REDIS_HOST="cart" \
    CATALOGUE_HOST="catalogue" \
    CATALOGUE_PORT="8080"
CMD ["cart",server.js]