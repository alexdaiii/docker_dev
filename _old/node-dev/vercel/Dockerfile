# Same in all node-dev containers
FROM node:alpine
RUN apk update
RUN apk upgrade
RUN apk add git
RUN apk add make

RUN npm install -g npm@latest
RUN npm install -g nodemon
RUN yarn global add vercel