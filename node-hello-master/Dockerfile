FROM openjdk:8-jdk-alpine
COPY package.json package.json
COPY package-lock.json package-lock.json
COPY . .
RUN npm start
CMD start index.js