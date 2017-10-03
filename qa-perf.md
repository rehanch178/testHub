| InstanceName           |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:-----------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER                |              |              |         |           |               |           |
| prod1-Manager          |      2       |      16      | /       |    57     | /mnt/local    |     0     |
| prod1-Manager          |      1       |      16      | /       |    44     | /mnt/local    |     0     |
| prod1-Manager          |      1       |      18      | /       |    26     | /mnt/local    |     0     |
| ES-HDFS                |              |              |         |           |               |           |
| prod1-worker-es-hdfs   |      3       |      45      | /mnt/es |    27     | /mnt/hdfs     |     1     |
| prod1-worker-es-hdfs   |      2       |      40      | /mnt/es |    15     | /mnt/hdfs     |     1     |
| ES-KIBANA              |              |              |         |           |               |           |
| prod1-worker-es-kibana |      3       |      52      | /mnt/es |    24     | /mnt/es_log   |    20     |
| prod1-worker-es-kibana |      4       |      51      | /mnt/es |    28     | /mnt/es_log   |    17     |
| prod1-worker-es-kibana |      3       |      53      | /mnt/es |    19     | /mnt/es_log   |    17     |
| NAMENODE               |              |              |         |           |               |           |
| prod1-worker-es-nn1    |      3       |      41      | /mnt/es |    19     | /mnt/hdfs_nn1 |     0     |
| prod1-worker-hdfs-nn2  |      4       |      44      | /mnt/es |    15     | /mnt/hdfs_nn2 |     0     |
| STORM                  |              |              |         |           |               |           |
| prod1-worker-storm     |      73      |      42      | /       |    32     | /mnt/local    |    14     |
| prod1-worker-storm     |      76      |      40      | /       |    32     | /mnt/local    |    14     |
| prod1-worker-storm     |      85      |      44      | /       |    32     | /mnt/local    |    16     |
| UTILITY                |              |              |         |           |               |           |
| prod1-worker-util      |      5       |      44      | /       |    59     | /mnt/local    |    13     |
| prod1-worker-util      |      6       |      39      | /       |    63     | /mnt/local    |    14     |
| ZOOKEEPER-KAFKA        |              |              |         |           |               |           |
| prod1-worker-zk-kafka  |      49      |      6       | /mnt/zk |     3     | /mnt/kafka    |     1     |
| prod1-worker-zk-kafka  |      46      |      5       | /mnt/zk |     3     | /mnt/kafka    |     1     |
| prod1-worker-zk-kafka  |      48      |      10      | /mnt/zk |     3     | /mnt/kafka    |     1     |
