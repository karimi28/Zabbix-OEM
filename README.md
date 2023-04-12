# Zabbix-OEM
Zabbix integration with Oracle Enterprise Manager.

We use OEM REST APIs to integrate Zabbix with OEM incident manager to use Zabbix automation capabilities. 

In "Zabbix OEM" template you must set four macros:

1. {$URL}: The OEM IP address or name 
2. {$PORT}: The port of OEM
3. {$USERNAME}: The OEMs username 
4. {$PASSWORD}: The OEMs password

Zabbix Severity integrate:

- Disaster=> Fatal
- High=> Critical
- Warning=> Warning








