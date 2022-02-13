# Spring actuator

依赖：

[pic1](http://img.mukewang.com/szimg/60fd094a09a7edf104700071.jpg)

功能：访问localhost:8080/actuator可以查看所有监控资源端点链接


status取值：

        UP:正常

        DOWN:遇到了问题，不正常;

        OUT_OF_SERVICE:资源未在使用，或者不该去使用;

        UNKNOWN:不知道


info端点:是个描述端点，而非监控端点;

常用端点：

http://img.mukewang.com/szimg/60fd0cd0094a01c007400510.jpg

配置：

http://img.mukewang.com/szimg/60fd0e230989ae8b08240384.jpg

# 配置文件       
## yml : yet another markup language => json 子集

1. 可读性更强，特别是数量多
2. 容器界更受欢迎
3. 可以保证配置的读取顺序


## 配置文件的集中管理方式
![picture 1](images/ae1dcb3811f4e474153e7b17048ccede70a5529873c6a9321ef9e6ee499e2a6d.png)  
