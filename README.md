# SolcastDomoticz
Solcast plugin for Domoticz
Domoticz plugin to fetch [Solcast](https://[Solcast](https://toolkit.solcast.com.au/) data<br><br>

Preliminary version, breaking changes to be expected!<br>
reads forecasted solar power prediction for a given solar panel installation<br><br>
Remark: if you have sets of panels in (very) different orientations, make a Hardware entry for each and make a Domoticz script to add them together<br>

## Prerequisites

- Follow the Domoticz guide on [Using Python Plugins](https://www.domoticz.com/wiki/Using_Python_plugins) to enable the plugin framework.

The following Python modules installed
```
sudo apt-get update
sudo apt-get install python3-requests
```

## Installation

1. Clone repository into your domoticz plugins folder
```
cd domoticz/plugins
git clone https://github.com/JanJaapKo/SolcastDomoticz
```
to update:
```
cd domoticz/plugins/SolarForecast
git pull https://github.com/JanJaapKo/SolcastDomoticz
```
2. Restart domoticz
3. Go to step configuration


## Configuration
Fill in the following parameters (mandatory unless marked optional):
