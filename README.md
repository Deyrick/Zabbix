## Zabbix

1. Copy the script file mtr.sh to the ExternalScripts folder on your Zabbix Server or Proxy.
2. Make the script executable: chmod +x mtr.py
3. Import the Template to your Zabbix Server.
4. Link the template to the target host. From there on Zabbix Server or Proxy will discover and monitor the hops between itself and the target's HOST IP using the {HOST.IP} macro.



## Template Status
0.Features
1.Imcp Check;
2.Snmp Check;
3.Uptime.
