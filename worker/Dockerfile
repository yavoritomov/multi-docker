FROM node:14.14.0-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
#RUN npm audit fix
COPY . .
CMD ["npm", "run", "start"]