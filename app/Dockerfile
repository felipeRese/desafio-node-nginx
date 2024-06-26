FROM node

WORKDIR /src/

COPY ./src/ /src/

RUN npm install

COPY ./wait-for-it.sh .

RUN chmod +x ./wait-for-it.sh;

EXPOSE 3000
