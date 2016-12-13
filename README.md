# AVROra
Tools for helping management VMware vSphere

## AVROra release plan

release 1.0 - goal monitoring:
* Local agent app for run on ESXi host monitoring available space of mounted datastores.
* Local agent app sending statistics on central instance.
* Local agent app cashing statistics on Sqlite file.
* Central instance collect statistics from agents.
* Central instance have Web UI for see monitoring status and statistics.
* Central instance have notification module (Email)

release 1.1 - goal tuning:
* vSphere Performance tuning
* Integration with VMtools
* Shrink VMDK

release 2.0 - goal management:
* Deploy VM from OVA
* Copy VM
* Clone VM
* Make templates from VM and deploy VM from template
* Post deploy VM tuning

release 2.1 - goal integration:
* AVROra REST API
* Run custom esxcli commands on ESXi
