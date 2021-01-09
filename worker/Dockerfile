FROM node:14.14.0-alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
#this will read start script from package.json
CMD ["npm", "run", "start"]
