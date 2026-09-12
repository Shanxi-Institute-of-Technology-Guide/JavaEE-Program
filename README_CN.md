# Java EE 练习

本目录包含基于 Maven 的 Java Web 与数据库练习模块。

> 课程说明：本目录收录课程实验或课程作业的解决方案。

## 模块

- `bean/`：JavaBean 练习
- `jdbc/`：JDBC 数据库访问练习
- `trans/`：事务处理练习

## 构建

在模块目录中执行构建：

```powershell
cd jdbc
mvn clean package
```

每个模块都有自己的 `pom.xml`。运行依赖数据库的示例前，请先配置数据库连接属性。