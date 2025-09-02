# grafana-router-monitoring
MikroTik Router(RB750Gr3) Monitoring: WAN/LAN Ports, SNMP, Rsyslog, InfluxDB, Telegraf &amp; Grafana

This project provides a comprehensive monitoring solution for MikroTik routers, capturing both WAN and LAN performance metrics along with system logs for visualization and analysis in Grafana.

By combining SNMP, Telegraf, InfluxDB, and Rsyslog, you can track router health, network activity, and troubleshoot issues with clear dashboards.

Features
* WAN & LAN Port Monitoring
  ** Interface throughput (Tx/Rx)

Packet drops, errors, and utilization

Real-time and historical traffic trends

System Metrics via SNMP

CPU usage, memory consumption

System uptime and temperature

Router identity (sysName)

Syslog Collection with Rsyslog

Centralized log aggregation from MikroTik

Event monitoring (auth, firewall, DHCP, etc.)

Easy filtering and correlation with metrics

Network Activity Tracking

ICMP ping query time and response

DNS resolver query latency

Device activity on LAN interfaces

Visualization in Grafana
