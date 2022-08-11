# Firewall Monitoring

In order to control the performance of a project and maintain its status, it is necessary to monitor different layers of the project. One of the most important part of network hardwares is firewalls that must be controlled instantly and the device information displayed on the dashboard.

The mentioned dashboard includes the following item:
- Hostname
- OS Version
- Uptime
- HA System Mode
- HA Auto Sync
- CPU Usage
- Memory Usage
- Input / Output Data Rate
- Port Summary (Name, Index, Alias, Status, IP Address, Network Mask, Bandwidth, Type, In Errors, Out Errors)
- HA States (Index, Hostname, CPU Usage, Memory Usage, Net Usage, Session Count, Sync Status)


In the pictures below, you can see the dashboard visualizations:

![image](https://user-images.githubusercontent.com/43276746/178458898-d6a6ab92-3dbf-4a67-a4ad-57c7eacda184.png)
![image](https://user-images.githubusercontent.com/43276746/178459021-7ecf72ed-7ec9-4755-b020-ff9c28dde393.png)
![image](https://user-images.githubusercontent.com/43276746/178459306-ccb68fa2-040e-46d1-9883-6e50b3973a8e.png)

It should be noted that the SNMP V3 protocol has been used to monitor these devices over Grafana platform.

Requirements:
- Grafana: https://grafana.com/grafana/download
- InfluxDB & Telegraf: https://portal.influxdata.com/downloads/

Remember:
- At first you need to apply your informations in both of dashoboard and configuration (YOUR-IP, YOUR-NAME, USERNAME, YOUR-AUTH-PASSWORD, YOUR-PRIV-PASSWORD)
- To use snmp configurations you need to load their mib files
