FROM node:alpine

# set the working direction
WORKDIR /app

# install app dependencies
COPY package.json /app

COPY package-lock.json /app

RUN npm install

# add app
COPY . /app

# start app
CMD ["npm", "start"]
