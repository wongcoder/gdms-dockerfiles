FROM node:8

RUN mkdir /frontend
WORKDIR /frontend

RUN git clone https://github.com/wongcoder/GDRFF.git

WORKDIR GDRFF/gdrffapp

RUN npm install

EXPOSE 80
EXPOSE 3000

CMD npm start

