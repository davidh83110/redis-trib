# redis-trib
For older version redis-trib which supported set password on creating.

Clone older version of `redis-trib.rb` which is [0781f056b9](https://github.com/otherpirate/redis/blob/0781f056b99fa88cb56861f9660bef4e2088d3ca/src/redis-trib.rb) from redis official github.

Supports to set `--password` when creating a cluster.

```
redis-trib.rb create --password stupidpass --replicas 1 172.20.0.101:6379 172.20.0.102:6379 172.20.0.103:6379 172.20.0.104:6379
```


