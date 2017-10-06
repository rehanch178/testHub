| InstanceName         |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:---------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER              |              |              |         |           |               |           |
| qa4-Manager          |      1       |      25      | /       |    77     | /mnt/local    |     0     |
| qa4-Manager          |      1       |      18      | /       |    26     | /mnt/local    |     0     |
| qa4-Manager          |      1       |      19      | /       |    26     | /mnt/local    |     0     |
| ES-HDFS              |              |              |         |           |               |           |
| qa4-worker-es-hdfs   |      0       |      37      | /mnt/es |    13     | /mnt/hdfs     |     2     |
| qa4-worker-es-hdfs   |      0       |      36      | /mnt/es |    15     | /mnt/hdfs     |     2     |
| ES-KIBANA            |              |              |         |           |               |           |
| qa4-worker-es-kibana |      2       |      53      | /mnt/es |    15     | /mnt/es_log   |    48     |
| qa4-worker-es-kibana |      1       |      53      | /mnt/es |    15     | /mnt/es_log   |    47     |
| qa4-worker-es-kibana |      1       |      51      | /mnt/es |    13     | /mnt/es_log   |    44     |
| NAMENODE             |              |              |         |           |               |           |
| qa4-worker-es-nn1    |      1       |      34      | /mnt/es |    13     | /mnt/hdfs_nn1 |     0     |
| qa4-worker-hdfs-nn2  |      1       |      39      | /mnt/es |    10     | /mnt/hdfs_nn2 |     0     |
| STORM                |              |              |         |           |               |           |
| qa4-worker-storm     |      78      |      75      | /       |    33     | /mnt/local    |    14     |
| qa4-worker-storm     |      88      |      86      | /       |    33     | /mnt/local    |    16     |
| qa4-worker-storm     |      82      |```diff-98```      | /       |    33     | /mnt/local    |    15     |
| UTILITY              |              |              |         |           |               |           |
| qa4-worker-util      |      1       |      33      | /       |    69     | /mnt/local    |    14     |
| qa4-worker-util      |      1       |      40      | /       |    66     | /mnt/local    |    14     |
| ZOOKEEPER-KAFKA      |              |              |         |           |               |           |
| qa4-worker-zk-kafka  |      44      |      6       | /mnt/zk |     2     | /mnt/kafka    |     0     |
| qa4-worker-zk-kafka  |      43      |      6       | /mnt/zk |     2     | /mnt/kafka    |     0     |
| qa4-worker-zk-kafka  |      43      |      6       | /mnt/zk |     1     | /mnt/kafka    |     0     |
