FROM node:latest
COPY backend-example-docker/ . 
EXPOSE 8000
ENV FRONT_URL=http://localhost:5000
RUN npm install
CMD npm start
