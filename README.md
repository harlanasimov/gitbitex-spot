<p align="center"><img width="40%" src="https://getbitex.oss-cn-beijing.aliyuncs.com/projects/image/logo.svg" /></p>

[![Go Report Card](https://goreportcard.com/badge/github.com/gitbitex/gitbitex-spot)](https://goreportcard.com/report/github.com/gitbitex/gitbitex-spot)

GitBitEx is an open source cryptocurrency exchange.

## Architecture
TODO

## Dependencies
* MySql (**BINLOG[ROW format]** enabled)
* Kafka
* Redis

## Install
### Server
* git clone https://github.com/harlanasimov/gitbitex-spot.git
* Create database and make sure **BINLOG[ROW format]** enabled
* Execute ddl.sql
* Modify conf.json
* Run go build
* Run ./gitbitex-spot
### Web
* git clone https://github.com/harlanasimov/gitbitex-web.git
* Run `npm install`
* Run `npm start`
* Run `npm run build` to build production
