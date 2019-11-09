FROM node:12.13-alpine

WORKDIR /usr/src/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY package.json /usr/src/app/package.json
RUN npm install

COPY . .

CMD [ "npm", "run", "start" ]
