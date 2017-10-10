| InstanceName         |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:---------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER              |              |              |         |           |               |           |
| qa7-Manager          |      6       |      19      | /       |    28     | /mnt/local    |     0     |
| qa7-Manager          |      4       |      17      | /       |    25     | /mnt/local    |     0     |
| qa7-Manager          |      5       |      17      | /       |    25     | /mnt/local    |     0     |
| ES-HDFS              |              |              |         |           |               |           |
| qa7-worker-es-hdfs   |      1       |      26      | /mnt/es |     0     | /mnt/hdfs     |     0     |
| qa7-worker-es-hdfs   |      1       |      25      | /mnt/es |     0     | /mnt/hdfs     |     0     |
| ES-KIBANA            |              |              |         |           |               |           |
| qa7-worker-es-kibana |      2       |      43      | /mnt/es |     0     | /mnt/es_log   |     0     |
| qa7-worker-es-kibana |      2       |      42      | /mnt/es |     0     | /mnt/es_log   |     0     |
| qa7-worker-es-kibana |      1       |      38      | /mnt/es |     0     | /mnt/es_log   |     0     |
| NAMENODE             |              |              |         |           |               |           |
| qa7-worker-es-nn1    |      3       |      32      | /mnt/es |     0     | /mnt/hdfs_nn1 |     0     |
| qa7-worker-hdfs-nn2  |      1       |      29      | /mnt/es |     0     | /mnt/hdfs_nn2 |     0     |
| STORM                |              |              |         |           |               |           |
| qa7-worker-storm     |      99      |      60      | /       |    28     | /mnt/local    |    28     |
| qa7-worker-storm     |      95      |      51      | /       |    28     | /mnt/local    |    27     |
| qa7-worker-storm     |      98      |      53      | /       |    27     | /mnt/local    |    28     |
| UTILITY              |              |              |         |           |               |           |
| qa7-worker-util      |      1       |      34      | /       |    35     | /mnt/local    |    27     |
| qa7-worker-util      |      2       |      35      | /       |    38     | /mnt/local    |    27     |
| ZOOKEEPER-KAFKA      |              |              |         |           |               |           |
| qa7-worker-zk-kafka  |      71      |      9       | /mnt/zk |     3     | /mnt/kafka    |     0     |
| qa7-worker-zk-kafka  |      72      |      9       | /mnt/zk |     3     | /mnt/kafka    |     0     |
| qa7-worker-zk-kafka  |      55      |      32      | /mnt/zk |     3     | /mnt/kafka    |     0     |

Disk Utilization by ES is: 0%
Disk Utilization by ES_LOG is: 0%
Disk Utilization by HDFS is: 0%
Disk Utilization by ZOOKEEPER is: 3%
Disk Utilization by KAFKA is: 0%
