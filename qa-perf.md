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
| qa4-worker-es-kibana |      2       |      56      | /mnt/es |    15     | /mnt/es_log   |    49     |
| qa4-worker-es-kibana |      1       |      54      | /mnt/es |    15     | /mnt/es_log   |    47     |
| qa4-worker-es-kibana |      1       |      53      | /mnt/es |    13     | /mnt/es_log   |    44     |
| NAMENODE             |              |              |         |           |               |           |
| qa4-worker-es-nn1    |      2       |      35      | /mnt/es |    13     | /mnt/hdfs_nn1 |     0     |
| qa4-worker-hdfs-nn2  |      0       |      37      | /mnt/es |    10     | /mnt/hdfs_nn2 |     0     |
| STORM                |              |              |         |           |               |           |
| qa4-worker-storm     |      84      |      54      | /       |    33     | /mnt/local    |    14     |
| qa4-worker-storm     |      86      |      90      | /       |    33     | /mnt/local    |    16     |
| qa4-worker-storm     |      83      |      92      | /       |    33     | /mnt/local    |    15     |
| UTILITY              |              |              |         |           |               |           |
| qa4-worker-util      |      1       |      33      | /       |    69     | /mnt/local    |    14     |
| qa4-worker-util      |      1       |      41      | /       |    66     | /mnt/local    |    14     |
| ZOOKEEPER-KAFKA      |              |              |         |           |               |           |
| qa4-worker-zk-kafka  |      44      |      6       | /mnt/zk |     2     | /mnt/kafka    |     0     |
| qa4-worker-zk-kafka  |      44      |      6       | /mnt/zk |     2     | /mnt/kafka    |     0     |
| qa4-worker-zk-kafka  |      45      |      6       | /mnt/zk |     3     | /mnt/kafka    |     0     |

Disk Utilization by ES is: 10%
Disk Utilization by ES_LOG is: 44%
Disk Utilization by HDFS is: 2%
Disk Utilization by ZOOKEEPER is: 3%
Disk Utilization by KAFKA is: 0%
---------------------------------------
| InstanceName         |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:---------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER              |              |              |         |           |               |           |
| qa5-Manager          |      3       |      26      | /       |    67     | /mnt/local    |     0     |
| qa5-Manager          |      2       |      20      | /       |    27     | /mnt/local    |     0     |
| qa5-Manager          |      1       |      17      | /       |    26     | /mnt/local    |     0     |
| ES-HDFS              |              |              |         |           |               |           |
| qa5-worker-es-hdfs   |      31      |      62      | /mnt/es |    51     | /mnt/hdfs     |    12     |
| qa5-worker-es-hdfs   |      27      |      63      | /mnt/es |    44     | /mnt/hdfs     |    12     |
| ES-KIBANA            |              |              |         |           |               |           |
| qa5-worker-es-kibana |      39      |      54      | /mnt/es |    68     | /mnt/es_log   |    27     |
| qa5-worker-es-kibana |      35      |      55      | /mnt/es |    46     | /mnt/es_log   |    27     |
| qa5-worker-es-kibana |      26      |      55      | /mnt/es |    48     | /mnt/es_log   |    34     |
| NAMENODE             |              |              |         |           |               |           |
| qa5-worker-es-nn1    |      35      |      65      | /mnt/es |    64     | /mnt/hdfs_nn1 |     0     |
| qa5-worker-hdfs-nn2  |      40      |      58      | /mnt/es |    63     | /mnt/hdfs_nn2 |     0     |
| STORM                |              |              |         |           |               |           |
| qa5-worker-storm     |      90      |      89      | /       |    42     | /mnt/local    |    24     |
| qa5-worker-storm     |      91      |      92      | /       |    35     | /mnt/local    |    34     |
| qa5-worker-storm     |      93      |      90      | /       |    37     | /mnt/local    |    26     |
| UTILITY              |              |              |         |           |               |           |
| qa5-worker-util      |      2       |      30      | /       |    54     | /mnt/local    |    14     |
| qa5-worker-util      |      2       |      32      | /       |    60     | /mnt/local    |    15     |
| ZOOKEEPER-KAFKA      |              |              |         |           |               |           |
| qa5-worker-zk-kafka  |      39      |      14      | /mnt/zk |     7     | /mnt/kafka    |    24     |
| qa5-worker-zk-kafka  |      49      |      25      | /mnt/zk |    13     | /mnt/kafka    |    24     |
| qa5-worker-zk-kafka  |      42      |      7       | /mnt/zk |    11     | /mnt/kafka    |    24     |

Disk Utilization by ES is: 63%
Disk Utilization by ES_LOG is: 34%
Disk Utilization by HDFS is: 12%
Disk Utilization by ZOOKEEPER is: 11%
Disk Utilization by KAFKA is: 24%
---------------------------------------
| InstanceName         |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:---------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER              |              |              |         |           |               |           |
| qa6-Manager          |      10      |      17      | /       |    75     | /mnt/local    |     0     |
| qa6-Manager          |      6       |      19      | /       |    26     | /mnt/local    |     0     |
| qa6-Manager          |      7       |      22      | /       |    27     | /mnt/local    |     0     |
| ES-HDFS              |              |              |         |           |               |           |
| qa6-worker-es-hdfs   |      0       |      63      | /mnt/es |    37     | /mnt/hdfs     |    20     |
| qa6-worker-es-hdfs   |      0       |      66      | /mnt/es |    46     | /mnt/hdfs     |    22     |
| ES-KIBANA            |              |              |         |           |               |           |
| qa6-worker-es-kibana |      1       |      50      | /mnt/es |    44     | /mnt/es_log   |    36     |
| qa6-worker-es-kibana |      2       |      49      | /mnt/es |    35     | /mnt/es_log   |    39     |
| qa6-worker-es-kibana |      2       |      50      | /mnt/es |    29     | /mnt/es_log   |    33     |
| NAMENODE             |              |              |         |           |               |           |
| qa6-worker-es-nn1    |      0       |      49      | /mnt/es |    42     | /mnt/hdfs_nn1 |     0     |
| qa6-worker-hdfs-nn2  |      2       |      57      | /mnt/es |    32     | /mnt/hdfs_nn2 |     0     |
| STORM                |              |              |         |           |               |           |
| qa6-worker-storm     |      76      |      54      | /       |    36     | /mnt/local    |    20     |
| qa6-worker-storm     |      77      |      49      | /       |    36     | /mnt/local    |    18     |
| qa6-worker-storm     |      85      |      54      | /       |    36     | /mnt/local    |    24     |
| UTILITY              |              |              |         |           |               |           |
| qa6-worker-util      |      1       |      28      | /       |    91     | /mnt/local    |    15     |
| qa6-worker-util      |      1       |      26      | /       |    99     | /mnt/local    |    14     |
| ZOOKEEPER-KAFKA      |              |              |         |           |               |           |
| qa6-worker-zk-kafka  |      46      |      10      | /mnt/zk |     2     | /mnt/kafka    |     0     |
| qa6-worker-zk-kafka  |      47      |      62      | /mnt/zk |     2     | /mnt/kafka    |     0     |
| qa6-worker-zk-kafka  |      47      |      6       | /mnt/zk |     2     | /mnt/kafka    |     0     |

Disk Utilization by ES is: 32%
Disk Utilization by ES_LOG is: 33%
Disk Utilization by HDFS is: 22%
Disk Utilization by ZOOKEEPER is: 2%
Disk Utilization by KAFKA is: 0%
------------------------------------
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
| qa7-worker-es-kibana |      1       |      42      | /mnt/es |     0     | /mnt/es_log   |     0     |
| qa7-worker-es-kibana |      2       |      42      | /mnt/es |     0     | /mnt/es_log   |     0     |
| qa7-worker-es-kibana |      1       |      38      | /mnt/es |     0     | /mnt/es_log   |     0     |
| NAMENODE             |              |              |         |           |               |           |
| qa7-worker-es-nn1    |      3       |      32      | /mnt/es |     0     | /mnt/hdfs_nn1 |     0     |
| qa7-worker-hdfs-nn2  |      1       |      29      | /mnt/es |     0     | /mnt/hdfs_nn2 |     0     |
| STORM                |              |              |         |           |               |           |
| qa7-worker-storm     |      99      |      59      | /       |    28     | /mnt/local    |    28     |
| qa7-worker-storm     |      95      |      50      | /       |    28     | /mnt/local    |    27     |
| qa7-worker-storm     |      98      |      54      | /       |    27     | /mnt/local    |    27     |
| UTILITY              |              |              |         |           |               |           |
| qa7-worker-util      |      1       |      34      | /       |    35     | /mnt/local    |    27     |
| qa7-worker-util      |      2       |      35      | /       |    37     | /mnt/local    |    27     |
| ZOOKEEPER-KAFKA      |              |              |         |           |               |           |
| qa7-worker-zk-kafka  |      71      |      9       | /mnt/zk |     4     | /mnt/kafka    |     0     |
| qa7-worker-zk-kafka  |      72      |      9       | /mnt/zk |     4     | /mnt/kafka    |     0     |
| qa7-worker-zk-kafka  |      55      |      32      | /mnt/zk |     4     | /mnt/kafka    |     0     |

Disk Utilization by ES is: 0%
Disk Utilization by ES_LOG is: 0%
Disk Utilization by HDFS is: 0%
Disk Utilization by ZOOKEEPER is: 4%
Disk Utilization by KAFKA is: 0%
-------------------------------------
| InstanceName             |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:-------------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER                  |              |              |         |           |               |           |
| qa-perf-Manager          |      2       |      19      | /       |    88     | /mnt/local    |     0     |
| qa-perf-Manager          |      1       |      19      | /       |    27     | /mnt/local    |     0     |
| qa-perf-Manager          |      19      |      23      | /       |    28     | /mnt/local    |     0     |
| ES-HDFS                  |              |              |         |           |               |           |
| qa-perf-worker-es-hdfs   |      10      |      55      | /mnt/es |    49     | /mnt/hdfs     |    16     |
| qa-perf-worker-es-hdfs   |      14      |      54      | /mnt/es |    71     | /mnt/hdfs     |    17     |
| ES-KIBANA                |              |              |         |           |               |           |
| qa-perf-worker-es-kibana |      25      |      44      | /mnt/es |    69     | /mnt/es_log   |    36     |
| qa-perf-worker-es-kibana |      30      |      47      | /mnt/es |    70     | /mnt/es_log   |    30     |
| qa-perf-worker-es-kibana |      14      |      42      | /mnt/es |    42     | /mnt/es_log   |    85     |
| NAMENODE                 |              |              |         |           |               |           |
| qa-perf-worker-es-nn1    |      17      |      43      | /mnt/es |    51     | /mnt/hdfs_nn1 |     1     |
| qa-perf-worker-hdfs-nn2  |      14      |      57      | /mnt/es |    64     | /mnt/hdfs_nn2 |     0     |
| STORM                    |              |              |         |           |               |           |
| qa-perf-worker-storm     |      80      |      76      | /       |    40     | /mnt/local    |    19     |
| qa-perf-worker-storm     |      75      |      83      | /       |    40     | /mnt/local    |    21     |
| qa-perf-worker-storm     |      85      |      75      | /       |    40     | /mnt/local    |    26     |
| UTILITY                  |              |              |         |           |               |           |
| qa-perf-worker-util      |      1       |      37      | /       |    65     | /mnt/local    |    14     |
| qa-perf-worker-util      |      2       |      40      | /       |    72     | /mnt/local    |    14     |
| ZOOKEEPER-KAFKA          |              |              |         |           |               |           |
| qa-perf-worker-zk-kafka  |      43      |      13      | /mnt/zk |     1     | /mnt/kafka    |     6     |
| qa-perf-worker-zk-kafka  |      43      |      7       | /mnt/zk |     1     | /mnt/kafka    |     6     |
| qa-perf-worker-zk-kafka  |      45      |      7       | /mnt/zk |     1     | /mnt/kafka    |     5     |

Disk Utilization by ES is: 64%
Disk Utilization by ES_LOG is: 85%
Disk Utilization by HDFS is: 17%
Disk Utilization by ZOOKEEPER is: 1%
Disk Utilization by KAFKA is: 5%
-----------------------------------
| InstanceName           |  Avg-cpu(%)  |  Avg-Mem(%)  | Disk    |  Used(%)  | Disk          |  Used(%)  |
|:-----------------------|:------------:|:------------:|:--------|:---------:|:--------------|:---------:|
| MANAGER                |              |              |         |           |               |           |
| prod1-Manager          |      2       |      17      | /       |    58     | /mnt/local    |     0     |
| prod1-Manager          |      1       |      18      | /       |    92     | /mnt/local    |     0     |
| prod1-Manager          |      1       |      19      | /       |    26     | /mnt/local    |     0     |
| ES-HDFS                |              |              |         |           |               |           |
| prod1-worker-es-hdfs   |      3       |      49      | /mnt/es |    34     | /mnt/hdfs     |     2     |
| prod1-worker-es-hdfs   |      2       |      55      | /mnt/es |    19     | /mnt/hdfs     |     2     |
| ES-KIBANA              |              |              |         |           |               |           |
| prod1-worker-es-kibana |      2       |      53      | /mnt/es |    31     | /mnt/es_log   |    39     |
| prod1-worker-es-kibana |      4       |      55      | /mnt/es |    36     | /mnt/es_log   |    42     |
| prod1-worker-es-kibana |      2       |      53      | /mnt/es |    26     | /mnt/es_log   |    35     |
| NAMENODE               |              |              |         |           |               |           |
| prod1-worker-es-nn1    |      2       |      47      | /mnt/es |    26     | /mnt/hdfs_nn1 |     0     |
| prod1-worker-hdfs-nn2  |      3       |      48      | /mnt/es |    20     | /mnt/hdfs_nn2 |     0     |
| STORM                  |              |              |         |           |               |           |
| prod1-worker-storm     |      80      |      54      | /       |    36     | /mnt/local    |    19     |
| prod1-worker-storm     |      79      |      49      | /       |    36     | /mnt/local    |    17     |
| prod1-worker-storm     |      87      |      52      | /       |    36     | /mnt/local    |    23     |
| UTILITY                |              |              |         |           |               |           |
| prod1-worker-util      |      1       |      36      | /       |    30     | /mnt/local    |    15     |
| prod1-worker-util      |      1       |      41      | /       |    40     | /mnt/local    |    15     |
| ZOOKEEPER-KAFKA        |              |              |         |           |               |           |
| prod1-worker-zk-kafka  |      50      |      6       | /mnt/zk |     4     | /mnt/kafka    |     4     |
| prod1-worker-zk-kafka  |      46      |      6       | /mnt/zk |     4     | /mnt/kafka    |     5     |
| prod1-worker-zk-kafka  |      49      |      27      | /mnt/zk |     5     | /mnt/kafka    |     5     |

Disk Utilization by ES is: 20%
Disk Utilization by ES_LOG is: 35%
Disk Utilization by HDFS is: 2%
Disk Utilization by ZOOKEEPER is: 5%
Disk Utilization by KAFKA is: 5%
