# spring-boot-api
url = https://github.com/spring-guides/gs-rest-service.git

sudo mvn clean package

sudo java -jar target/gs-rest-service-0.1.0.jar

http://127.0.0.1:8080/greeting/?name=super

kill other processes running on port 8080
sudo ps aux | awk '/jenkins/{print $2}' | xargs sudo kill -9


