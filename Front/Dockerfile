FROM node:18
WORKDIR /usr/src/drive-select-front

# Install dependencies
COPY ./Front .

COPY ../.env .env

RUN npm install

RUN npm run build

EXPOSE 80
CMD ["npm", "run", "preview"]