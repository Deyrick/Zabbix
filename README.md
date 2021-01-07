# Zabbix

Copy the script file mtr.sh to the ExternalScripts folder on your Zabbix Server or Proxy.
Make the script executable: chmod +x mtr.py
Import the Template to your Zabbix Server.
Link the template to the target host. From there on Zabbix Server or Proxy will discover and monitor the hops between itself and the target's HOST IP using the {HOST.IP} macro.


#Template Status
Imcp Check
Snmp Check
Uptime
