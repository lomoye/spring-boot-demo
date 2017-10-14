FROM java:8

ADD @project.build.finalName@.jar app.jar
EXPOSE 6379
CMD java -jar app.jar