SPARK
=====

## Spark Configuration
[http://spark.apache.org/docs/latest/configuration.html](http://spark.apache.org/docs/latest/configuration.html)
* /etc/dse/spark/spark-defaults.conf

```
 spark.eventLog.enabled                 true
 spark.eventLog.dir                     hdfs://192.168.100:9000/spark/eventlog
 spark.history.fs.logDirectory          hdfs://192.168.100:9000/spark/eventlog
 spark.history.fs.cleaner.enabled       true
 spark.history.fs.cleaner.interval      14d
 spark.history.fs.cleaner.maxAge        30d
```

## Monitoring
[http://spark.apache.org/docs/1.4.1/monitoring.html](http://spark.apache.org/docs/1.4.1/monitoring.html)
* ./sbin/start-history-server.sh

## Run Spark History Server
1. Get DSE Patch
  * [dse](https://github.com/kevinduraj/spark/blob/master/dse) 
2. Replace DSE
  * /usr/bin/dse
3. Run Spark History Server
  * dse spark-history-server start

[Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
