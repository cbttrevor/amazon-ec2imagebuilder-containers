FROM node

ADD ["trevortest/", "/app/"]

WORKDIR /app

#RUN ls -lGa /app

RUN npm install && npm run build

ENTRYPOINT [ "npm", "start" ]