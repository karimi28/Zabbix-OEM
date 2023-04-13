# Zabbix-OEM
Zabbix integration with Oracle Enterprise Manager.

We use OEM REST APIs to integrate Zabbix with OEM incident manager to use Zabbix automation capabilities.

In "Zabbix OEM" template you must set four macros:

    {$OEM.URL}: The OEM IP address or name
    {$OEM.PORT}: The port of OEM
    {$USERNAME}: The OEMs username
    {$PASSWORD}: The OEMs password

Zabbix Severity integrate:

    Disaster=> Fatal
    High=> Critical
    Warning=> Warning

Tested on Zabbix 6.0.8
