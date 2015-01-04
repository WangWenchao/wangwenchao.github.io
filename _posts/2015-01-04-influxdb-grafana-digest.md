---
layout: post
title InfluxDB and Grafana first Digest
---

After I read the article on the [rubychina](https://ruby-china.org/topics/23470) and then have a motivation to have a try the InfluxDB and Grafana

As the introduction of InfluxDB <http://influxdb.com/> , which is An open-source, distributed, time series database
with no external dependencies

And the Grafana <http://grafana.org/> , which is An open source, feature rich metrics dashboard and graph editor for 
Graphite, InfluxDB & OpenTSDB

InfluxDB and Grafana can work together very well 

install tutorial **(base on the Mac OX)**

1 install InfluxDB  <http://influxdb.com/docs/v0.8/introduction/installation.html>

``` shell
brew update
brew install influxdb
brew info influxdb
influxdb -config=/usr/local/etc/influxdb.conf
```
then open the browser <http://127.0.0.1:8083/>


2. install the Grafana  from source , use grunt to build the project 

```
git clone https://github.com/grafana/grafana.git
cd grafana
brew  install node 
npm install -g grunt-cli
npm install
grunt build
```

3. start the grafana by

``` shell
python -m SimpleHTTPServer
```

then <http://127.0.0.1:8000>

4. Add InfluxDB to your App  
  development libaray for Ruby --- influxdb gem


