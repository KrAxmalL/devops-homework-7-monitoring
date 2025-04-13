# Homework 7 - Monitoring

## Grafana Dashboards
Created Grafana Dashboards are located inside the `grafana_dashboards` folder. They are imported into Grafana on the startup together with the Prometheus and Loki datasources. They also can be imported into any Grafana instance as a JSON. There are 2 available dashboards:
- `system-info-from-prometheus-and-node-exporter.json` - dashboards which shows basic system information using data obtained from Prometheus (and Node Exporter).
- `logs-from-loki.json` - dashboard which shows logs obtained from Linux system log files through Loki (and Promtail).

## Accessing the deployed services
- http://localhost:3000 - accessing Grafana
- http://localhost:9090 - accessing Prometheus
- http://localhost:9100 - accessing Node Exporter
- http://localhost:3200 - accessing Promtail