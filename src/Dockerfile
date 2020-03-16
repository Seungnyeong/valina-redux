FROM node:alpine
ARG dir
WORKDIR '/'
COPY ./package.json .
RUN yarn 
CMD ["yarn", "start", ]