# spring-boot-demo
    .
    ├── common
    │   ├── pom.xml
    │   └── src
    │       ├── main
    │       │   ├── java
    │       │   │   └── com
    │       │   │       └── hz
    │       │   │           └── spring
    │       │   │               └── demo
    │       │   │                   ├── constant
    │       │   │                   └── enum
    │       │   └── resources
    │       └── test
    │           └── java
    ├── exception
    │   ├── pom.xml
    │   └── src
    │       ├── main
    │       │   ├── java
    │       │   │   └── com
    │       │   │       └── hz
    │       │   │           └── spring
    │       │   │               └── demo
    │       │   │                   ├── biz
    │       │   │                   ├── controller
    │       │   │                   ├── remote
    │       │   │                   └── system
    │       │   └── resources
    │       └── test
    │           └── java
    ├── facade
    │   ├── pom.xml
    │   └── src
    │       ├── main
    │       │   ├── java
    │       │   │   └── com
    │       │   │       └── hz
    │       │   │           └── spring
    │       │   │               └── demo
    │       │   │                   ├── feign
    │       │   │                   └── sdk
    │       │   └── resources
    │       └── test
    │           └── java
    ├── pom.xml
    ├── utils
    │   ├── pom.xml
    │   └── src
    │       ├── main
    │       │   ├── java
    │       │   └── resources
    │       └── test
    │           └── java
    └── web
        ├── pom.xml
        └── src
            ├── main
            │   ├── java
            │   │   └── com
            │   │       └── hz
            │   │           └── spring
            │   │               └── demo
            │   │                   ├── DemoApplication.java
            │   │                   ├── application
            │   │                   │   ├── module
            │   │                   │   │   ├── DemoService.java
            │   │                   │   │   └── impl
            │   │                   │   │       └── DemoServiceImpl.java
            │   │                   │   └── module1
            │   │                   ├── config
            │   │                   │   ├── aliyun
            │   │                   │   ├── baidu
            │   │                   │   └── webmvc
            │   │                   ├── domain
            │   │                   │   ├── model
            │   │                   │   └── service
            │   │                   ├── infrastructure
            │   │                   │   ├── aspect
            │   │                   │   ├── job
            │   │                   │   ├── mq
            │   │                   │   └── persistence
            │   │                   │       ├── module
            │   │                   │       │   ├── dao
            │   │                   │       │   ├── mapper
            │   │                   │       │   └── model
            │   │                   │       ├── module1
            │   │                   │       └── module2
            │   │                   └── interfaces
            │   │                       ├── bo
            │   │                       ├── controller
            │   │                       ├── dto
            │   │                       ├── request
            │   │                       └── vo
            │   └── resources
            └── test
                └── java
