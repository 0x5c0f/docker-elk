# docker-elk  

- `docker-compose` 是按照官方文档编写的，不过我不太会写`docker-compose`,语法借鉴了其他项目的`docker-compose` 写法，现目前我这边稳定运行。  
- 项目还有一个是 `filebeat` 推送 `java` 日志到 `elasticsearch` 的格式模板。   
- 项目使用的镜像都是较新的`7.5.0`版本  
- 新的版本已经支持一些插件安装,比如说`_head`插件，如果要使用的话，可以使用`google`浏览器的插件`ElasticSearch Head`  

## 部署 

```bash
$> git clone https://github.com/0x5c0f/docker-elk.git
$> cd docker-elk
$> docker-compose up -d  
```
