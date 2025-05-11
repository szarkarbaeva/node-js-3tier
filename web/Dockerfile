FROM node:18

WORKDIR /usr/src/app

COPY package*.json .

RUN npm install

COPY . .

ENV PORT=3000 \
    API_HOST=http://13.217.200.102:3001

EXPOSE 3000

CMD ["npm","start"]
