| InstanceName         |   Avg-CPU-Usage |   Avg-Mem-Usage | Disk        |   Used(%) | Disk                |   Used(%) |
|:---------------------|----------------:|----------------:|:------------|----------:|:--------------------|----------:|
| qa7-Manager          |               6 |              16 | /           |        28 | /mnt/local          |         0 |
| qa7-Manager          |               5 |              17 | /           |        26 | /mnt/local          |         0 |
| qa7-Manager          |               5 |              17 | /mnt/local  |         0 | /                   |        26 |
| qa7-worker-es-hdfs   |               8 |              38 | /mnt/es     |         3 | /mnt/hdfs           |         0 |
| qa7-worker-es-hdfs   |               6 |              34 | /mnt/es     |         2 | /mnt/hdfs           |         0 |
| qa7-worker-es-kibana |              10 |              44 | /mnt/es     |         2 | /mnt/es_log         |        10 |
| qa7-worker-es-kibana |              11 |              48 | /mnt/es_log |        13 | /mnt/es             |         3 |
| qa7-worker-es-kibana |               7 |              40 | /mnt/es     |         2 | /mnt/es_log         |        10 |
| qa7-worker-es-nn1    |               8 |              41 | /mnt/es     |         3 | /mnt/hdfs_namenode1 |         0 |
| qa7-worker-hdfs-nn2  |               8 |              43 | /mnt/hdfs   |         1 | /mnt/hdfs_namenode2 |         0 |
| qa7-worker-storm     |              94 |              56 | /           |        27 | /mnt/local          |        27 |
| qa7-worker-storm     |              97 |              68 | /mnt/local  |        27 | /                   |        27 |
| qa7-worker-storm     |              98 |              63 | /mnt/local  |        28 | /                   |        27 |
| qa7-worker-util      |               1 |              31 | /mnt/local  |        27 | /                   |        36 |
| qa7-worker-util      |               2 |              32 | /mnt/local  |        27 | /                   |        36 |
| qa7-worker-zk-kafka  |              61 |              29 | /mnt/kafka  |         7 | /mnt/zk             |         7 |
| qa7-worker-zk-kafka  |              64 |               9 | /mnt/zk     |         4 | /mnt/kafka          |         6 |
| qa7-worker-zk-kafka  |              69 |              10 | /mnt/zk     |         7 | /mnt/kafka          |         6 |
Disk utilization by Elasticsearch is: 3%
Disk utilization by Elasticsearch log is: 10%
Disk utilization by HDFS is: 1%
Disk utilization by Zookeeper is: 7%
Disk utilization by Kafka is: 6%
