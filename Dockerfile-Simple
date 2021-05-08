FROM node:12
WORKDIR /usr/src/app

COPY . ./

# building the app
RUN npm i
RUN npm run build

EXPOSE 3000

# Running the app
CMD [ "npx", "next", "start" ]
