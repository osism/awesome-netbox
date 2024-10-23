# Awesome NetBox

A curated list of awesome [NetBox](https://github.com/netbox-community/netbox) resources.

[NetBox](https://github.com/netbox-community/netbox) is an infrastructure resource modeling (IRM) tool designed to empower network automation.

## Automation

* [e-breuninger/terraform-provider-netbox](https://github.com/e-breuninger/terraform-provider-netbox) - Terraform provider to interact with Netbox
* [netbox-community/ansible_modules](https://github.com/netbox-community/ansible_modules) - NetBox modules for Ansible using Ansible Collections
* [smutel/terraform-provider-netbox](https://github.com/smutel/terraform-provider-netbox) - Terraform provider for Netbox

## Deployment

* [bootc/netbox-chart](https://github.com/bootc/netbox-chart) - A Helm chart for NetBox
* [gmazoyer/ansible-role-netbox](https://github.com/gmazoyer/ansible-role-netbox) - Ansible role that installs on Debian/Ubuntu
* [lae/ansible-role-netbox](https://github.com/lae/ansible-role-netbox) - Cross-platform Ansible role for deploying NetBox
* [linuxserver/docker-netbox](https://github.com/linuxserver/docker-netbox) - Docker image of NetBox
* [netbox-community/netbox-docker](https://github.com/netbox-community/netbox-docker) - Docker image of NetBox
* [osism/ansible-collection-services](https://github.com/osism/ansible-collection-services) - Ansible role for deploying NetBox inside a container

## Utilities

* [minitriga/Netbox-Device-Type-Library-Import](https://github.com/minitriga/Netbox-Device-Type-Library-Import) - The library is intended to be your friend and help you import all the device-types defined within the the NetBox Device Type Library Repository
* [netbox-community/devicetype-library](https://github.com/netbox-community/devicetype-library) - A collection of community-sourced DeviceType definitions
* [Solvik/netbox-agent](https://github.com/Solvik/netbox-agent) - Project aims to create hardware automatically into Netbox based on standard tools (dmidecode, lldpd, parsing /sys/, etc)

## Synchronization

* [TheNetworkGuy/netbox-zabbix-sync](https://github.com/TheNetworkGuy/netbox-zabbix-sync) - Python script to syncronise Netbox devices to Zabbix
* [bb-Ricardo/netbox-sync](https://github.com/bb-Ricardo/netbox-sync) - A tool to sync data from different sources (VMware, Redfish) to a NetBox instance
* [scaleway/netbox2netshot](https://github.com/scaleway/netbox2netshot) - Inventory synchronization tool between Netbox and Netshot
* [stfc/Netbox-utils](https://github.com/stfc/Netbox-utils) - Scripts and Utilities for querying and updating information in Netbox

## Exporters

* [Solcon/netbox-gitlab](https://github.com/Solcon/netbox-gitlab) - GitLab export to Ansible Inventory for NetBox

## SDKs

* [benclaussen/NetboxPS](https://github.com/benclaussen/NetboxPS) - Powershell module for Netbox
* [hexa2k9/netbox-php](https://github.com/hexa2k9/netbox-php) - PHP API client library
* [jagter/python-netbox](https://github.com/jagter/python-netbox) - Python Netbox client
* [netbox-community/go-netbox](https://github.com/netbox-community/go-netbox) - Go API client library
* [netbox-community/pynetbox](https://github.com/netbox-community/pynetbox) - Python API client library
* [ninech/netbox-client-ruby](https://github.com/ninech/netbox-client-ruby) - Ruby API client library
* [timeforplanb123/anac](https://github.com/timeforplanb123/anac) - Python Async API client library

## CLIs

* [nbcli/nbcli](https://codeberg.org/nbcli/nbcli) - NetBox Command-line Client using the pynetbox module

## Plugins

* [Alef-Burzmali/netbox-data-flows](https://github.com/Alef-Burzmali/netbox-data-flows) - Document data flows between systems and applications
* [DanSheps/netbox-secretstore](https://github.com/DanSheps/netbox-secretstore) - Continuation of the NetBox secrets app
* [FlxPeters/netbox-plugin-prometheus-sd](https://github.com/FlxPeters/netbox-plugin-prometheus-sd) - Plugin to use Netbox as service discovery for Prometheus
* [auroraresearchlab/netbox-dns](https://github.com/auroraresearchlab/netbox-dns) - Plugin for managing zone, nameserver and record inventory
* [gardunha/netbox-routeros](https://github.com/gardunha/netbox-routeros) - Netbox plugin for auto-configuring Mikrotik RouterOS devices
* [iDebugAll/nextbox-ui-plugin](https://github.com/iDebugAll/nextbox-ui-plugin) - Topology visualization plugin
* [k01ek/netbox-bgp](https://github.com/k01ek/netbox-bgp) - Plugin for BGP related objects documentation
* [k01ek/netbox-qrcode](https://github.com/k01ek/netbox-qrcode) - Plugin for generate QR codes for objects: Rack, Device, Cable
* [mattieserver/netbox-topology-views](https://github.com/mattieserver/netbox-topology-views) - A netbox plugin that draws topology views
* [minitriga/axians-netbox-plugin-pdu](https://github.com/minitriga/axians-netbox-plugin-pdu) - Plugin to get PDU information
* [mlebreuil/netbox-contract](https://github.com/mlebreuil/netbox-contract) - Plugin that adds a contracts and invoices model
* [netboxlabs/netbox-branching](https://github.com/netboxlabs/netbox-branching) - git-like branching functionality for NetBox
* [networktocode/ntc-netbox-plugin-onboarding](https://github.com/networktocode/ntc-netbox-plugin-onboarding) - Plugin to easily onboard new devices using Netmiko, NAPALM & Django-RQ
* [renatoalmeidaoliveira/nbservice](https://github.com/renatoalmeidaoliveira/nbservice) - Plugin for ITSM service mapping
* [ryanmerolle/netbox-acls](https://github.com/ryanmerolle/netbox-acls) - NetBox Access Lists Plugin
* [sjm-steffann/netbox-ddns](https://github.com/sjm-steffann/netbox-ddns) - Dynamic DNS Connector for NetBox
* [tobiasge/netbox-initializers](https://github.com/tobiasge/netbox-initializers) - Netbox Initializers Plugin
* [vapor-ware/netbox-virtual-circuit-plugin](https://github.com/vapor-ware/netbox-virtual-circuit-plugin) - Plugin for NetBox that supports Virtual Circuit management

## Integrations

* [StackStorm-Exchange/stackstorm-netbox](https://github.com/StackStorm-Exchange/stackstorm-netbox) - NetBox plugin for StackStorm
* [netdevopsbr/netbox-proxbox](https://github.com/netdevopsbr/netbox-proxbox) - Netbox Plugin for integration between Proxmox and Netbox
* [oz123/coredns-netbox-plugin](https://github.com/oz123/coredns-netbox-plugin) - A CoreDNS plugin to get dns records from NetBox
* [wvandeun/nornir_netbox](https://github.com/wvandeun/nornir_netbox) - NetBox plugin for Nornir

## Forks

* [nautobot/nautobot](https://github.com/nautobot/nautobot) - Nautobot is a Network Source of Truth and Network Automation Platform, initially developed as a fork of NetBox v2.10.4

## Inspirations

* [wobcom/cosmo](https://github.com/wobcom/cosmo) - Cosmo is another fairy that converting Netbox data into input data for our (wobcom) templating solution
