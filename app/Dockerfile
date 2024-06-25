FROM node

WORKDIR /src/

COPY ./src/ /src/

RUN npm install

ENTRYPOINT [ "npm", "start" ]

EXPOSE 3000