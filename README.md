# NTT Data Consultance
<center>
    <img src="./imgs/main-logo.png">
</center>

For performance testing Demo purposes

Visit K6 [Load test types](https://k6.io/docs/test-types/load-test-types/) for more information

## To Run Project
```
docker-compose up -d influxdb grafana
docker-compose run k6 run /scripts/stress-test.js
```
## Where to visualize after spinng up the containers

- Grafana Url:
http://localhost:3000/

- Influx DB Url:
http://localhost:8888/


## More about the Dashboard
The dashboard in /dashboards is adapted from the excellent K6 / Grafana dashboard here:
https://grafana.com/grafana/dashboards/2587

## Software used:
- K6
- Docker
- Kibana
- Grafana