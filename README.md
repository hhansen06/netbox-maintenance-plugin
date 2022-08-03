# NetBox Maintenante Plugin
[Netbox](https://github.com/netbox-community/netbox) plugin for Maintenance Contracts related objects documentation.

## Compatibility

|             |       |
|-------------|-------|
| NetBox 3.2.4  | 0.1.0 |

## Installation

The plugin is available as a Python package in pypi and can be installed with pip  

```
pip install netbox_maintenancecontract_plugin
```
Enable the plugin in /opt/netbox/netbox/netbox/configuration.py:
```
PLUGINS = ['netbox_maintenancecontract_plugin']
```
Restart NetBox and add `netbox_maintenancecontract_plugin` to your local_requirements.txt

## Configuration
none
## Screenshots

BGP Session
![BGP Session](docs/img/bgp_sess.png)

BGP Sessions
![BGP Session Table](docs/img/bgp_sess_list.png)

ASN
![ASN](docs/img/asn.png)

ASNs
![ASN Table](docs/img/asn_list.png)

Community
![Community](docs/img/commun.png)

Peer Group
![Peer Group](docs/img/peer_group.png)
