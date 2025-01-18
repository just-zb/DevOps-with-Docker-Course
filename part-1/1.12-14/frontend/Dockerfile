FROM node:16.20.2

EXPOSE 5000

COPY . .


RUN npm install

ENV REACT_APP_BACKEND_URL=http://localhost:8081

RUN npm run build

RUN npm install -g serve

RUN cd ./build

CMD serve -s -l 5000 build
