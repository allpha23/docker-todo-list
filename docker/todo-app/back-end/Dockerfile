FROM node:17-alpine
WORKDIR /app
EXPOSE 3001
ADD node_modules.tar.gz /app
COPY . .
ENTRYPOINT [ "npm", "start" ]
