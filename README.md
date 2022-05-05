# problem

问题记录

## 编辑器问题

#### 1. mvnw : 无法将“mvnw”项识别为 cmdlet、函数、脚本文件或可运行程序的名称。请检查名称的拼写，如果包括路径，请确保路径正确，然后再试一次。

背景： 在安装新的idea编辑器后， 使用指令mvnw clean spring-boot:run, 报错.

原因: 还没搞清楚

解决方法: 使用mvn代替mvnw， mvn clean spring-boot:run 正常运行