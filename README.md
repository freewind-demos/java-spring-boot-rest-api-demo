Java Spring Boot Rest Api Demo
==============================

如何使用SpringBoot来定义RestApi

```
brew install httpie
./mvnw package
java -jar target/demo-0.0.1-SNAPSHOT.jar
```

```
http POST https://agile-wave-92007.herokuapp.com/api/messages text=aaa
http POST https://agile-wave-92007.herokuapp.com/api/messages text=bbb

http POST https://agile-wave-92007.herokuapp.com/api/messages text=aa##bb

http GET https://agile-wave-92007.herokuapp.com/api/messages

http GET https://agile-wave-92007.herokuapp.com/api/messages/0
```
