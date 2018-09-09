##### Lucence
每个regionserver使用Lucene保存以及检索查询
##### Elasticsearch
建立index保存在ES存储中；客户端双写或者cp同步数据
##### Solr
solr保存索引数据，可以部署；与hbase共用HDFS，ZK
##### Pheonix
在HBase之上建立多个二级索引；索引数据以及元数据存储在HBase表中
##### 其他DB保存索引
大量的原数据集合保存在HBase
#####自建HBase索引
自建HBase表做全局索引；利用客户端双写实现同步