FROM node:8-alpine
RUN mkdir /app
WORKDIR /app
ADD . /app/
RUN npm install
ENV NODE_ENV=production
CMD ["npm","start"]
