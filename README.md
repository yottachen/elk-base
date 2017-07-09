#ELK base

The repo aim to provide a template help you create a ELK cluster quickly.


### Requirements
* [Docker](http://docker.io/)
* [Docker compose](https://github.com/docker/compose/releases)

### Instructions
* Start cluster
```
  docker-compose up
```

* Stop cluster
```
  docker-compose stop
  # or
  docker-compose down
```

### Stack & Versions
* [x][kibana 5.2](https://www.elastic.co/guide/en/kibana/current/index.html)
* [x][logstash 5.2](https://www.elastic.co/guide/en/logstash/current/index.html)
* [x][Filebeat 5.2](https://www.elastic.co/guide/en/beats/filebeat/current/index.html)
* [x][elasticsearch 5.2](https://www.elastic.co/guide/en/elasticsearch/reference/5.2/index.html)

* [][xPack: 5.2](https://www.elastic.co/guide/en/x-pack/current/index.html)
* [][search-guard 5](https://github.com/floragunncom/search-guard/tree/5.0.0)

### Images
* [kibana](https://github.com/elastic/kibana-docker)
* [filebeat](https://github.com/elastic/beats-docker)
* [logstash](https://github.com/elastic/logstash-docker)
* [elasticsearch](https://github.com/elastic/elasticsearch-docker)

### Aganippe
* [docker-elk](https://github.com/deviantony/docker-elk)
* [spujadas-elk-docker](https://github.com/spujadas/elk-docker)
* [readthedocs-elk-docker](https://elk-docker.readthedocs.io/)

### Ref
* [ELK中文社区](http://elasticsearch.cn/)
* [ELK官方文档](https://www.elastic.co/guide/index.html)
* [Elastic Stack中文指南](https://kibana.logstash.es/content/)
* [elasticsearch中文指南](https://es.xiaoleilu.com/010_Intro/00_README.html)

* [ELK栈搭建指南](http://www.jianshu.com/p/934c457a333c)
* [通天塔之ELK学习](http://wdxtub.com/2016/11/19/babel-log-analysis-platform-0/)
* [ELK集群搭建](http://linuxg.blog.51cto.com/4410110/1843114)
* [ELK集群部署](http://linuxg.blog.51cto.com/4410110/1843114)
* [Graylog简介](https://testerhome.com/topics/3026)
* [Rancher容器日志方案简述](http://www.dockerinfo.net/215.html)
* [Filebeat使用简介](http://tonybai.com/2016/03/25/ship-docker-container-log-with-filebeat/)
