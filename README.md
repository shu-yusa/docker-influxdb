# Docker InfluxDB
A docker sample for InfluxDB and Chronograf.

## Requirements

* Docker
* Docker Compose

## Setup
For InfluxDB client from host.
```bash
brew install influxdb
```

## Launch InfluxDB
Launch by
```bash
docker-compose up
```
Then, InfluxDB runs on http://localhost:8086, and Chronograf runs on http://localhost:8888.  
Open http://localhost:8888 by a browser to enter the Chronograf dashboard.
