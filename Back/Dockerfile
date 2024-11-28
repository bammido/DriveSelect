FROM node:18
WORKDIR /usr/src/drive-select-back

COPY ./Back .
RUN npm i -g npm
RUN npm i
COPY ../.env .env
RUN npm run build
EXPOSE 8080
CMD ["npm","run", "start:docker"]