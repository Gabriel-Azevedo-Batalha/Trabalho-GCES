FROM node:16-alpine
WORKDIR /frontend
COPY package.json /frontend/
RUN rm -rf node_modules package-lock.json
RUN npm install
COPY . /frontend/