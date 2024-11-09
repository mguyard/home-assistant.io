---
title: Diagral
description: Instructions on how to setup Diagral devices within Home Assistant.
ha_category:
  - Alarm
  - Hub
ha_release: 2024.12
ha_iot_class: Cloud Polling
ha_domain: diagral
ha_platforms:
  - alarm_control_panel
ha_config_flow: true
ha_dhcp: false
ha_integration_type: hub
---

Home Assistant has support to integrate your [Diagral](https://www.diagral.fr/) devices.

{% include integrations/config_flow.md %}

{% include integrations/option_flow.md %}

## Alarm control panel

The Diagral alarm control panel platform allows you to control your [Diagral](https://www.diagral.fr/) Alarms.

The requirements are :

- to have a [DIAG56AAX box](https://www.diagral.fr/commande/box-alerte-et-pilotage) to interact with Diagral Cloud.
- to have a account/password and PIN code to enought right to interact with Alarm.

Diagral alarm panel entity can have the following states :

- __Disarmed__: The alarm is disarmed (off).
- __Armed away__: The alarm is armed in away mode.
- __Armed home__: The alarm is armed in home mode (presence mode).

## Supported platforms

- [Alarm control panel](/integrations/alarm_control_panel/)
