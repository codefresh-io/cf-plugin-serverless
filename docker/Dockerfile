FROM node:9-alpine

# set serverless version
ARG SERVERLESS_VER
ENV SERVERLESS_VER ${SERVERLESS_VER:-1.27.3}

# install serverless
RUN echo "Building with serverless version: " ${SERVERLESS_VER}
RUN npm install -g serverless@${SERVERLESS_VER}