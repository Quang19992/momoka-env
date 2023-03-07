# momoka-env
Quick docker-compose that setup env for [Quang19992/momoka](https://github.com/Quang19992/momoka)

## Notice
This is for testing purpose and not for production, therefore all the databases are exposed to the internet with no password

Expected you should either:
* Setup a firewall
* Add password env
* Make the ports only exposed to local machine by editing the **ports** section
```
ports:
  - 127.0.0.1:xxx:xxx
  - ...
```
