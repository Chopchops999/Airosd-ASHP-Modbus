hardware used is waveshare RS485 to Eth, Modbus via TCP https://www.waveshare.com/wiki/RS485_TO_ETH_(B)?srsltid=AU7gw4XysHiihtr1WZk2C_OYDQYb_-JqiZw1Ubyg4P-Gm0FrDODOazqI
add Modbus integration via HA device intergrations
in File Editor:-
add a new "modbus" folder in home assistant folder 
Add the "modbus.Yaml" file to the modbus folder 
update HA "Configuration.yaml" file to inc a line for the Modbus and modbus.yaml file:-example "modbus: !include modbus.yaml"
update entity names etc to suit
view Airosd modbus address info for additional monitoring and control
add control to dashboard via thermostat cards
airosd wifi controller can be controlled via tuya smart life intergration, via cloud
