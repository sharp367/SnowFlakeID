# SnowFlakeID
java代码生成雪花ID, 项目基于springboot, HTTP访问接口, 返回ID

整个项目docker打包
blazings/snowflakeid

docker pull blazings/snowflakeid:1.0

docker run --restart=always -d -p 8080:8080 2ba8b4ef39

默认端口8080
访问地址: http://127.0.0.1:8080/get/id
