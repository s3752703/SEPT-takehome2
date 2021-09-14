FROM openjdk:8-jdk-alpine
ENV PORT=3000
WORKDIR ../node-hello-master
RUN addgroup -S spring && adduser -S spring -G spring
USER spring:spring
COPY package.json package.json
COPY package-lock.json package-lock.json
EXPOSE 3000