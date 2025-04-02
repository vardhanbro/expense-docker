FROM node:20
WORKDIR /opt/backend
COPY package.json ./
COPY *.js ./
#This below "install" will helps in installing the packages
RUN npm install
ENV DB_HOST="local"
CMD ["node" , "index.js"] 