FROM node:4.4.7
LABEL maintainer="phillipn101@gmail.com"
EXPOSE 8888
RUN mkdir -p /usr/src/app/
WORKDIR /usr/src/app/
COPY package.json /usr/src/app/
RUN npm install
CMD ["nodemon", "start"]
VOLUME /usr/src/app/src/
