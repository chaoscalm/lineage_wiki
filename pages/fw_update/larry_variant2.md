---
sidebar: home_sidebar
title: Update firmware on larry
folder: fw_update
permalink: /devices/larry/fw_update/variant2/
device: larry_variant2
---
{% assign device = site.data.devices[page.device] %}
{% capture path %}templates/device_specific/{{ device.firmware_update }}.md{% endcapture %}
{% include {{ path }} %}
