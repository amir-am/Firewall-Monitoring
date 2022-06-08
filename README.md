# Firewall Monitoring

In order to control the performance of a project and maintain its status, it is necessary to monitor different layers of the project. One of the most important part of network hardwares is firewalls that must be controlled instantly and the device information displayed on the dashboard.

It should be noted that the SNMP V3 protocol has been used to monitor these devices over Grafana platform.

The mentioned dashboard includes the following item:
- Hostname
- Uptime
- OS Version
- CPU Usage
- Memory Usage
- Input / Output Data Rate
- Errors
- Discards
- Port Summary

In the pictures below, you can see the dashboard visualizations:

Requirements:
- Grafana: https://grafana.com/grafana/download
- InfluxDB & Telegraf: https://portal.influxdata.com/downloads/

Remember:
- At first you need to apply your informations in both of dashoboard and configuration (YOUR-IP, YOUR-NAME, USERNAME, YOUR-AUTH-PASSWORD, YOUR-PRIV-PASSWORD)
- To use snmp configurations you need to load their mib files
