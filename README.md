# docker-compose_pypimanager

## usage

```
HOST_IP=`ip route get 8.8.8.8 | awk '{print $7; exit}'`
export HOST_IP=$HOST_IP && docker-compose up -d
```