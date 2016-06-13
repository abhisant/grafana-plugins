Grafana plugin for [Druid](http://druid.io/) real-time OLAP database works for Grafana 3.0.

## Configuration

Add new Druid Datasource with url to Druid broker instance. For example http://druid.internal/druid

## Status

This plugin is built on the top of an existing Druid plugin which used to work on Grafana 2.6. With the UI changes done form 2.6 to 3.0 the existing plugin stopped working. Made changes to have it work on Grafana 3.0. It supports timeseries, group by, topN and Select queries.
