# 给springcloud项目使用 

## 1、请阅读以下两个项目

> 因为是基于他们的项目的

https://github.com/weiangongsi/ueditor-spring-boot-starter

>此项项目就加了
url-prefix-as: http://localhost:8001 #"/"结尾 映射地址 别名
为什么？因为vue项目8080端口。springcloud项目是8001端口
而用以前 这种方式 url-prefix: /file/ #"/"结尾 映射地址 
vue项目就会把 /file 解析成localhost:8080/file
而真实的图片在localhost:8001/file


vue-vue-ueditor-wrap
https://github.com/HaoChuan9421/vue-ueditor-wrap




# 2、依赖新的maven-jar包（已上传阿里云镜像）


    <!-- springboot-ueditor 富文本编辑器 -->
    <dependency>
        <groupId>org.kd</groupId>
        <artifactId>ueditor-vue-spring-boot-starter</artifactId>
        <version>1.0-M1</version>
    </dependency>




