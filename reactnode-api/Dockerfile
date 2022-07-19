FROM node:14
WORKDIR /reactnode-api   
COPY ["package*.json","./"]
RUN npm install
COPY . .
CMD npm start