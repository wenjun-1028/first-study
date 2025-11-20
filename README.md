# 我的第一个 Java 项目

这是一个简单的 Java 项目示例，用于学习 GitHub 使用。

## 项目结构
my-project/
├── src/
│ └── main/
│ └── java/
│ └── com/
│ └── example/
│ └── Main.java
├── pom.xml
└── README.md
## 如何运行
1. 确保已安装 Java 11 和 Maven
2. 编译项目：`mvn clean compile`
3. 运行程序：`mvn exec:java -Dexec.mainClass="com.example.Main"`

## 自动化构建
本项目配置了 GitHub Actions，每次代码推送时会自动编译和测试。
