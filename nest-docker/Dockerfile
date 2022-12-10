FROM node:16.18-alpine
WORKDIR /app
COPY . .

RUN npm i && npm run build
CMD npm run start:prod