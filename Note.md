# 笔记

## 命令

```shell
# 查看依赖树
mvn dependency:tree -Dincludes=org.springframework*

# 运行spring-boot工程
mvn spring-boot:run

# curl请求
curl http://127.0.0.1:8080/
```



使用Maven Wrapper

mvnw

```shell
# 通常使用mvn命令
mvn clean install
# 使用Maven Wrapper
./mvnw clean install
./mvnw.cmd clean install
# 启动spring-boot
sh mvnw spring-boot:run
```



java -jar

```shell
# 执行
java -jar target/demo-0.0.1-SNAPSHOT.jar
```

