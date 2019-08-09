FROM openjdk:8
ADD /target/booking-app.war booking-app.war
EXPOSE 8085
ENTRYPOINT ["java", "-jar", "booking-app.war"] 