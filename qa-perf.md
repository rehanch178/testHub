| InstanceName           |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:-----------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER                |              |              |         |           |               |           |
| prod1-Manager          |      2       |      18      | /       |    57     | /mnt/local    |     0     |
| prod1-Manager          |      2       |      16      | /       |    65     | /mnt/local    |     0     |
| prod1-Manager          |      1       |      18      | /       |    26     | /mnt/local    |     0     |
| ES-HDFS                |              |              |         |           |               |           |
| prod1-worker-es-hdfs   |      10      |      44      | /mnt/es |    30     | /mnt/hdfs     |     2     |
| prod1-worker-es-hdfs   |      6       |      45      | /mnt/es |    17     | /mnt/hdfs     |     2     |
| ES-KIBANA              |              |              |         |           |               |           |
| prod1-worker-es-kibana |      13      |      49      | /mnt/es |    28     | /mnt/es_log   |    60     |
| prod1-worker-es-kibana |      16      |      49      | /mnt/es |    32     | /mnt/es_log   |    50     |
| prod1-worker-es-kibana |      16      |      50      | /mnt/es |    22     | /mnt/es_log   |    48     |
| NAMENODE               |              |              |         |           |               |           |
| prod1-worker-es-nn1    |      10      |      44      | /mnt/es |    22     | /mnt/hdfs_nn1 |     0     |
| prod1-worker-hdfs-nn2  |      7       |      44      | /mnt/es |    18     | /mnt/hdfs_nn2 |     0     |
| STORM                  |              |              |         |           |               |           |
| prod1-worker-storm     |      72      |      38      | /       |    34     | /mnt/local    |    15     |
| prod1-worker-storm     |      83      |      45      | /       |    34     | /mnt/local    |    16     |
| prod1-worker-storm     |      85      |      46      | /       |    34     | /mnt/local    |    19     |
| UTILITY                |              |              |         |           |               |           |
| prod1-worker-util      |      1       |      40      | /       |    75     | /mnt/local    |    14     |
| prod1-worker-util      |      1       |      39      | /       |    77     | /mnt/local    |    14     |
| ZOOKEEPER-KAFKA        |              |              |         |           |               |           |
| prod1-worker-zk-kafka  |      48      |      6       | /mnt/zk |     4     | /mnt/kafka    |     0     |
| prod1-worker-zk-kafka  |      45      |      6       | /mnt/zk |     3     | /mnt/kafka    |     0     |
| prod1-worker-zk-kafka  |      48      |      18      | /mnt/zk |     3     | /mnt/kafka    |     0     |
