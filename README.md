# Brew-RED

A Node RED based, full electric RIMS controller, with 2 PIDs (Mash and HLT), 3 step mash timers, MQTT output of mash temperature
(I save it in a Influx and look in Grafana) and Twitter notifications when setpoints are reached or in case of a stuck mash.

The entire thing runs on a Raspberry Pi, two DS18B20 probes, 3 solidstate relays and is powered by an old ATX PSU.

Dashboard is designed to fit on a 7" touchscreen.

Add MQTT server if you want to log data. Add Twitter account if you want notifications.

Happy brewing
