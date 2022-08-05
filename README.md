# flume-ng-elasticsearch-sink
Flume-NG 1.9 Sink for Elasticsearch 7.8.0

# Requirements
* Flume-NG 1.9
* Elasticsearch 7.8.0

# Build
  Maven
  
# Describe
  采集Kafka数据到Es的Flume配置文件案例：kafkaToES.conf
  新增了一个间隔时间，设置多久去生成一个新的索引，避免单个索引的数据量过大
