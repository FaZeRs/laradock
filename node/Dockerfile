  
ARG NODE_VERSION
FROM node:${NODE_VERSION}

WORKDIR /var/www/bp-store

ENV PATH=/var/www/bp-store/node_modules/.bin:$PATH

#ARG LARADOCK_NODE_PATH_HOST
#Not work with external path
#COPY ${LARADOCK_NODE_PATH_HOST}/package.json /var/www
#RUN npm ci -qy

#CMD ["npm", "dev"]