# Next.js Dockerfile
FROM node:latest

WORKDIR /app

## Copy Json
COPY package.json ./

RUN npm install

COPY . .

RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]