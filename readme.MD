# 使用TomcatEmbeded 创建Web应用

## 1. docbase
JSP和静态网页位于项目根的webapp下，打包后将些目录复制到jar文件同级

## 2. appassembler-maven-plugin
项目中使用该插件，可以直接创建一个跨平台的应用。
在发布时需要保留target中的：bin,repo 及相应的jar,并复制webapp目录到target下

## 3. john_server.properties
用于配置启动端口，发布项目时，需要复制到target下。

