# Start or Stop the Services

These commands you must know when you using the Logstash of Websoft9

### Logstash

```shell
sudo systemctl start logstash-server
sudo systemctl stop logstash-server
sudo systemctl restart logstash-server
sudo systemctl status logstash-server

# you can use this debug mode if Logstash service can't run
logstash-server console
```

### MySQL

```shell
sudo systemctl start mysql
sudo systemctl stop mysql
sudo systemctl restart mysql
sudo systemctl status mysql
```

### Redis

```shell
systemctl start redis
systemctl stop redis
systemctl restart redis
systemctl status redis
```
