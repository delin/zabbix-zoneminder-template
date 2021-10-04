# zabbix-zoneminder-template
Zabbix Template for ZoneMinder (CCTV)

# Zabbix Template for ZoneMinder (CCTV)

## Setup

> See [Zabbix template operation](https://www.zabbix.com/documentation/6.0/manual/config/templates_out_of_the_box/http) for basic instructions.

1\. Link the template to the host.

2\. Customize the values of {$ZM.API_ENDPOINT}, {$ZM.USER}, {$ZM.PASSWORD}, {$ZM.MONITOR.MIN_BANDWIDTH} macros.

## Zabbix configuration

No specific Zabbix configuration is required.

### Macros used

|Name|Description|Default|
|----|-----------|-------|
|{$ZM.USER} |<p>ZoneMinder user login.</p> |`<change>` |
|{$ZM.PASSWORD} |<p>ZoneMinder user password.</p> |`<change>` |
|{$ZM.API_ENDPOINT} |<p>The URL of ZoneMinder API endpoint.</p> |`http://zoneminder.local/api` |
|{$ZM.MONITOR.MIN_BANDWIDTH} |<p>Minimum bandwidth in bytes allowed without triggers.</p> |`10240` |

## Template links

There are no template links in this template.

## Discovery rules

- Monitors

## Items collected

### Monitors

- Archived Event Disk Space
- Archived Events
- Capture Bandwidth
- Capture FPS
- Day Event Disk Space
- Day Events
- Function
- Height
- Host
- Hour Event Disk Space
- Hour Events
- Is Enabled
- Month Event Disk Space
- Month Events
- Notes
- Status
- StorageId
- Total Event Disk Space
- Total Events
- Week Event Disk Space
- Week Events
- Width

## Triggers

### Monitors
- Enabled
- Function Changed
- Low Bandwidth
- Status
