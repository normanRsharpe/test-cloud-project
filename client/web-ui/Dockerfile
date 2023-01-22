# Dockerfile for React app (web-ui)
#

# Build stage using node 16.13.1-alpine
FROM node:16.13.1-alpine as build-stage

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build

# Serve stage
FROM nginx:1.17.9-alpine as serve-stage

COPY --from=build-stage /app/build /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

# Path: client/web-ui/nginx.conf