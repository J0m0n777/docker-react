FROM node:alpine
WORKDIR /usr/jo
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm","start"]
