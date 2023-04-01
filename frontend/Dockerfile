FROM node:16.3.0-alpine3.13
WORKDIR /app
RUN npm install
EXPOSE 7878
CMD [ "npm", "run", "dev", "--", "--host", "0.0.0.0" ]