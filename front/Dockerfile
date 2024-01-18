FROM node:13.12.0-alpine as build
WORKDIR /src

COPY package*.json ./

RUN npm install --silent
COPY . ./

RUN npm run build


FROM nginx:alpine
EXPOSE 3000
COPY ./nginx/default.conf /etc/nginx/conf.d/default.conf
COPY --from=build /src/build /usr/share/nginx/html