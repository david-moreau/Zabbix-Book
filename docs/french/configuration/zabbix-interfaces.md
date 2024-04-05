# Interfaces

Lors de la création de votre host vous allez rapidement avoir besoin de lui spécifier une adresse IP ou un FQDN.

Cette configuration se trouve dans la zone `interface` de la vue `create host`.

Après avoir cliqué sur add, un menu déroulant vous demandera de sélectionner le type de l'interface.

![interfaces](../../configuration/image/zabbix-interfaces/interfaces.png)

|||
|--|--|
|Parameters|Description|
|Agent|Permet d'utiliser des items keys de type Zabbix Agent et Zabbix agent Active|
|SNMP|Permet de superviser le host via des items de type SNMP|
|JMX|Permet de superviser les application Java via les [JMX](https://www.zabbix.com/documentation/current/en/manual/config/items/itemtypes/jmx_monitoring) counter|
|IPMI|Permet de superviser l'IPMI via des items de type [IPMI checks](https://www.zabbix.com/documentation/current/en/manual/config/items/itemtypes/ipmi)|

???+ Note
    We will cover IPMI in more detail later in the Chapter [IPMI Monitoring](../extra-monitoring/IPMI-monitoring.md)
    We will cover JAVA in more detail later in the Chapter [IPMI Monitoring](../extra-monitoring/JAVA-monitoring.md)
    We will cover SNMP in more detail later in the Chapter [IPMI Monitoring](../extra-monitoring/SNMP-monitoring.md)