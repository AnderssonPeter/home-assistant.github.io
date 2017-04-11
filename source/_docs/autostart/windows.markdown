---
layout: page
title: "Autostart on Windows"
description: "Instructions how to setup Home Assistant to run as a service on Windows."
date: 2017-04-11 09:56
sidebar: true
comments: false
sharing: true
footer: true
redirect_from: /getting-started/autostart-windows/
---

### Installation
* Copy the `HomeAssistantService` folder to a location of choice for example `C:\Program files\HomeAssistantService\`
* Open cmd and go to the directory where you placed `HomeAssistantService`
* Run `HomeAssistantService install`, this installs it as a windows service.
* Provide the credentials for the current user when prompted (This is used to run the service as the current user)
* Run `HomeAssistantService start` this starts the service and in turn `Home Assistant`.

### Uninstall
* Open cmd and go to the directory where you placed `HomeAssistantService`
* First stop the service with `HomeAssistantService stop`
* Run `HomeAssistantService uninstall` to uninstall the service
