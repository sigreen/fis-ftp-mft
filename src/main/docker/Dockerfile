FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD fis-ftp-mft-1.0.0.jar app.jar
RUN touch /app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
