FROM maven:latest
RUN mkdir /shoeshop
WORKDIR /shoeshop
COPY . .
EXPOSE 8080
CMD [ "mvn", "spring-boot:run" ]