# esp_distance_sensor

Testing a disstance sensor wired into a NodeMCU that is flashed with Esphome and sending data back to HA.  The sensor reports in meters but I added the config to convert it on the NodeMCU and report in Inches to HA.  Eventually this will be used to monitor the salt level of my water softener system.

The wiring is self explanatory via the config yaml.  Sensor just needs 5V, Gnd, and two data pins which are outlined in the yaml.
