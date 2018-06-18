FROM node:9-alpine

# set serverless version
ARG SERVERLESS_VER
ENV SERVERLESS_VER ${SERVERLESS_VER:-1.27.3}

# install serverless
RUN npm install -g serverless@${SERVERLESS_VER}