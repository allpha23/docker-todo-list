FROM node:17-alpine
WORKDIR /app
EXPOSE 3000
ADD node_modules.tar.gz /app
COPY . .
ENTRYPOINT [ "npm", "start" ]
