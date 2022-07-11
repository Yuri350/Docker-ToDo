FROM node:14-alpine
ADD node_modules.tar.gz .
WORKDIR .
COPY . todobackend
EXPOSE 3001
ENTRYPOINT ["npm start"]