# pdd-power-sensor-hardware

find a way to do the following jobs

1. use esphome preferably or some other project
2. first boot of device, ask user to connect wifi using captive portal (this is simple)
3. investigate if web server can be dynamically enabled/disabled using physical button.
4. ask user to connect to wifi and input details like area, meter setting (smart/non-smart) and (flat/not flat) (consumer/commercial) and unique ID.
5. disable web server once settings are validated and first ping is sent to server.
6. OTA check server update to download .bin file
7. send half hourly "ping" containing payload.
