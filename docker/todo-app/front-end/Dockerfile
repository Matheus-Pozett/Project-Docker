FROM node:14-alpine
WORKDIR /app
EXPOSE 3000
ADD node_modules.tar.gz /
COPY src ./src
ENTRYPOINT [ "npm start" ]
