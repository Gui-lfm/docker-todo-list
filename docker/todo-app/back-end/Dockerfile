FROM node:14-alpine
WORKDIR /app

EXPOSE 3001
ADD node_modules.tar.gz .
COPY . /app
ENTRYPOINT [ "npm" ]
CMD [ "start" ]