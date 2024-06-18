FROM node:14-alpine

WORKDIR  /app

COPY react-frontend/package.json .

RUN npm install

RUN npm update


COPY react-frontend .

#EXPOSE 3000

ENTRYPOINT ["npm","start"]


