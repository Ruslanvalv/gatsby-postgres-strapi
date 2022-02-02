FROM node

WORKDIR /app

COPY ./package.json .

RUN   npm install && npm install -g gatsby-cli

COPY . .

EXPOSE  8000


CMD ["gatsby", "develop", "-H", "0.0.0.0"]