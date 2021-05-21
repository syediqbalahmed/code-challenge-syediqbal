FROM node:14
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV API_HOST=http://localhost:3001
ENV PORT=3000
EXPOSE 3000
CMD ["npm", "start" ]
