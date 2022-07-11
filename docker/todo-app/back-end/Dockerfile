FROM node:14-alpine
WORKDIR /
ADD node_modules.tar.gz .
COPY . todobackend
EXPOSE 3001
CMD ["npm", "start"]
