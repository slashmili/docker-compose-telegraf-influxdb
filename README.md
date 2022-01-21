This repo contains dokcker-compose file that brings up:

* Influxdb: Listening to [http://localhost:8086](http://localhost:8086). 
* Telegrag: Listening to localhost 8092/udp. It writes the state into Influxdb using influx http interface.



Username and password are stored in [./influxdb/env.env](./influxdb/env.env)


## Start-up

```
docker-compose up -d
```
