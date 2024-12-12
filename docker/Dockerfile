FROM openjdk:8-jdk

COPY . /app

WORKDIR /app

EXPOSE 8080


CMD ["java", "-Dserver.port=8080","-Dcsp.sentinel.dashboard.server=localhost:8080","-Dproject.name=sentinel-dashboard","-jar","sentinel-dashboard-1.8.8.jar"]


