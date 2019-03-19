# zookeeper-quorum
Example on how to set up ZooKeeper in two groups - using Confluent's docker images

The trick is to use the environment variable ZOOKEEPER_GROUPS like this

```
ZOOKEEPER_GROUPS: 1:2:3;4:5:6
```

