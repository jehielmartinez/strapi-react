FROM node:14

WORKDIR /usr/src/frontend

ENV PATH /app/node_modules/.bin:$PATH

COPY ["package.json", "package-lock.json", "/usr/src/frontend/"]

RUN npm install

COPY [".", "/usr/src/frontend/"]

CMD ["npm", "start"]