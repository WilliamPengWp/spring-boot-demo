# Spring Boot Hello World 應用程序

這是一個簡單的Spring Boot示例應用程序，提供一個Hello World端點。

## 如何運行

### 使用Gradle

```bash
./gradlew bootRun
```

## 測試應用程序

應用程序啟動後，您可以通過以下URL訪問Hello World端點：

```
http://localhost:8080/hello
```

## 專案結構

- `src/main/java/com/example/demo/DemoApplication.java`: 應用程序的主類
- `src/main/java/com/example/demo/controller/HelloController.java`: 包含Hello World端點的REST控制器 