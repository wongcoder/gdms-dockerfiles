FROM node:8
RUN mkdir /backend
WORKDIR /backend
RUN git clone https://github.com/dale-kim/gdbackend
WORKDIR gdbackend/
RUN npm i express pg
EXPOSE 5432
EXPOSE 3000
CMD node index.js
