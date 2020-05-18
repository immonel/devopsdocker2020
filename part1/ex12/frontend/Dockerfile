FROM node:latest
COPY frontend-example-docker/ .
EXPOSE 5000
ENV API_URL=http://localhost:8000
RUN npm install
CMD npm start
