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
![image](https://user-images.githubusercontent.com/43276746/172603092-78fceb08-9d0a-45fe-a556-00c7eef7e009.png)
![image](https://user-images.githubusercontent.com/43276746/172603261-ceaa3057-d498-457e-a59b-88b61feda760.png)
![image](https://user-images.githubusercontent.com/43276746/172603765-84f7d7ae-8a3f-407b-9b06-c2c05ed7c56e.png)


Requirements:
- Grafana: https://grafana.com/grafana/download
- InfluxDB & Telegraf: https://portal.influxdata.com/downloads/

Remember:
- At first you need to apply your informations in both of dashoboard and configuration (YOUR-IP, YOUR-NAME, USERNAME, YOUR-AUTH-PASSWORD, YOUR-PRIV-PASSWORD)
- To use snmp configurations you need to load their mib files
