FROM node:alpine
WORKDIR '/app'
COPY package.json .
RUN npm install
COPY . .
CMD ["npm","run","start"]
#Start cmd mentioned above can be find in package.json script section