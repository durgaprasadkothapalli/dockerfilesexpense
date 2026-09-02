# FROM node:20 AS builder
# WORKDIR /opt/server
# COPY package.json .
# COPY *.js .
# RUN npm install


# FROM node:20.18.0-alpine3.20
# EXPOSE 8080
# ENV DB_HOST="mysql"
# RUN addgroup -S expense && adduser -S expense -G expense && \
#     mkdir /opt/server && \
#     chown -R expense:expense /opt/server
# WORKDIR /opt/server
# COPY --from=builder /opt/server /opt/server
# USER expense
# CMD ["node", "index.js"]
# Before best practices implemented
# FROM node:20
# EXPOSE 8080
# ENV DB_HOST="mysql"
# RUN mkdir /opt/server
# WORKDIR /opt/server
# COPY package.json .
# COPY *.js .
# RUN npm install
# CMD ["node", "index.js"]

# FROM node:20 AS builder
# WORKDIR /opt/server
# COPY package.json .
# COPY *.js .
# RUN npm install


# FROM node:20.18.0-alpine3.20
# EXPOSE 8080
# ENV DB_HOST="mysql"
# RUN addgroup -S expense && adduser -S expense -G expense && \
#     mkdir /opt/server && \
#     chown -R expense:expense /opt/server
# WORKDIR /opt/server
# COPY --from=builder /opt/server /opt/server
# USER expense
# CMD ["node", "i


FROM node:20      # it take iamge from dockerhub image 
EXPOSE 8080         # give the port no. of contianer 
ENV DB_HOST="mysql"       # we take the path and palce the iamge
RUN mkdir /opt/server      # run the workdir of the image
WORKDIR /opt/server            copy the packge.json files
COPY package.json .
COPY *.js .                    # and copy the js files in current directory
RUN npm install             # install dependencies all to start the services
 CMD [ "node","index.js" ]      # index conncetion and 