FROM node:12.18.1
ENV NODE_ENV=production

WORKDIR /home/app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install --production

COPY . .

CMD [ "node", "script.js" ]
