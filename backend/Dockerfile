FROM node:current-alpine    
WORKDIR /index

COPY package*.json ./
RUN npm i --legacy-peer-deps

COPY . .
EXPOSE 8000
CMD ["node", "index.js"]