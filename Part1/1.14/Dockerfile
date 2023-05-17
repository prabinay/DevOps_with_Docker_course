FROM node:16-alpine

WORKDIR /app

COPY . .

RUN npm install --production


RUN npm run build

RUN npm install -g serve

EXPOSE 5000

ENV REACT_APP_BACKEND_URL=http://192.168.232.115:5000

CMD ["serve", "-s", "-l", "5000", "build"]









