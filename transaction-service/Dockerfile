FROM node:20
WORKDIR /app
COPY package*.json ./
COPY .env ./
RUN npm install
COPY . .
RUN npm run build
CMD npm start
#CMD ["node", "dist/main"]
#CMD ["npm", "run", "start:prod"]