# Zabbix-Templates EN
Some templates for Zabbix  
  
Zabbix 3.0:  
- **Richcomm Netmate Lite.xml** - Template for Richcomm Netmate Lite II SNMP UPS card. Used in Crown Smart UPS.  
- **Powerwalker SNMP Web Pro and Crown SNMP-MCY-EN.xml** - Template for Powerwalker SNMP Web Pro 1.1 cards and Crown SNMP-MCY-EN (UPS model CMUOA-350).  

Zabbix 6.0
- **Ippon SNMP II EPPC-MIB** - Template for Ippon 1-phase UPS like Innova RT II which use Ippon SNMP II card. Only 1 phase UPS are supported because there is no snmp discovery in this template.

# Zabbix-Templates RU
Несколько шаблонов для Zabbix
  
Zabbix 3.0:  
- **Richcomm Netmate Lite.xml** - шаблон для SNMP карт Richcomm Netmate Lite II. Применяются в ИБП Crown Smart UPS.
- **Powerwalker SNMP Web Pro and Crown SNMP-MCY-EN.xml** - Шаблон для SNMP карт Powerwalker SNMP Web Pro 1.1 cards и Crown SNMP-MCY-EN (модель ИБП CMUOA-350).  

Zabbix 6.0
- **Ippon SNMP II EPPC-MIB** - Шаблон для 1-фазных ИБП фирмы Ippon, использующих SNMP-карты Ippon SNMP II; например, Innova RT II. Шаблон подходит для мониторинга только 1-фазных ИБП, т.к. в нем нет обнаружения (в 3х-фазных ИБП показания по фазам находятся в SNMP-таблице отдельно по каждой фазе), т.к. такого ИБП для теста у меня нет.
