# Litter Robot Proxy — Home Assistant Add-On Repository

Custom Home Assistant add-on repository for the Litter Robot Proxy add-on.

## Installation

1. In Home Assistant, go to **Settings → Add-ons → Add-on Store**
2. Click the **⋮** menu → **Repositories**
3. Add this repository URL: https://github.com/adamjthompson/litter-robot-proxy-addon
4. Find **Litter Robot Proxy** in the store and click **Install**

## Add-ons included

| Add-on | Description |
|--------|-------------|
| [Litter Robot Proxy](litter-robot-proxy/) | Local MQTT proxy for Litter Robot 3 Connect devices |

## Requirements

- Home Assistant with Supervisor (HAOS or Supervised)
- Mosquitto broker add-on
- AdGuard Home or another local DNS server