| InstanceName           |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:-----------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER                |              |              |         |           |               |           |
| prod1-Manager          |      2       |      19      | /       |    57     | /mnt/local    |     0     |
| prod1-Manager          |      2       |      15      | /       |    74     | /mnt/local    |     0     |
| prod1-Manager          |      1       |      19      | /       |    26     | /mnt/local    |     0     |
| ES-HDFS                |              |              |         |           |               |           |
| prod1-worker-es-hdfs   |      6       |      48      | /mnt/es |    31     | /mnt/hdfs     |     1     |
| prod1-worker-es-hdfs   |      3       |      48      | /mnt/es |    17     | /mnt/hdfs     |     1     |
| ES-KIBANA              |              |              |         |           |               |           |
| prod1-worker-es-kibana |      15      |      51      | /mnt/es |    28     | /mnt/es_log   |    64     |
| prod1-worker-es-kibana |      18      |      53      | /mnt/es |    33     | /mnt/es_log   |    54     |
| prod1-worker-es-kibana |      5       |      53      | /mnt/es |    23     | /mnt/es_log   |    52     |
| NAMENODE               |              |              |         |           |               |           |
| prod1-worker-es-nn1    |      7       |      46      | /mnt/es |    23     | /mnt/hdfs_nn1 |     0     |
| prod1-worker-hdfs-nn2  |      5       |      46      | /mnt/es |    18     | /mnt/hdfs_nn2 |     0     |
| STORM                  |              |              |         |           |               |           |
| prod1-worker-storm     |      73      |      41      | /       |    34     | /mnt/local    |    15     |
| prod1-worker-storm     |      76      |      39      | /       |    34     | /mnt/local    |    17     |
| prod1-worker-storm     |      85      |      43      | /       |    34     | /mnt/local    |    20     |
| UTILITY                |              |              |         |           |               |           |
| prod1-worker-util      |      1       |      40      | /       |    82     | /mnt/local    |    14     |
| prod1-worker-util      |      1       |      32      | /       |    83     | /mnt/local    |    15     |
| ZOOKEEPER-KAFKA        |              |              |         |           |               |           |
| prod1-worker-zk-kafka  |      49      |      6       | /mnt/zk |     4     | /mnt/kafka    |     2     |
| prod1-worker-zk-kafka  |      46      |      6       | /mnt/zk |     4     | /mnt/kafka    |     2     |
| prod1-worker-zk-kafka  |      49      |      19      | /mnt/zk |     3     | /mnt/kafka    |     2     |
