# maven-demo

There are some demos show you how to build Java project with Maven.

用Maven编译Java项目的几个例子。

文章介绍：[使用maven编译Java项目](http://www.waylau.com/build-java-project-with-maven/)


# 注释


@张金晶：

使用流水线构建这个项目时，命令写：

mvn package -f ./demo2/pom.xml -Dmaven.test.skip=true -Dautoconfig.skip


