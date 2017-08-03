# zabbix_high.write.IOPS.disks
zabbix template for collecting high write IOPS statistics
Based on this template https://github.com/grundic/zabbix-disk-performance Many thanks to "grundic"


hwdiskIOPS.conf --- keys description. Copy file to "zabbix/zabbix_agentd.d" or copy content into main zabbix_agentd.conf
hwIO.py --- script for discovery
zabbix_high_write_iops.xml --- template, please import to zabbix-server 
