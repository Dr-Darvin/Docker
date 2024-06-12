# specify base image
FROM node:14-alpine

# install dependancies
WORKDIR /usr/app
COPY ./ ./
RUN npm install

# default command
CMD [ "npm","start" ]

