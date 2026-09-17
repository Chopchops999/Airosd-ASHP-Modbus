add Modbus integration 
in File Editor:-
add a new modbus folder in home assistant folder 
Add the Yaml file to the modbus folder 
update HA Configuration.yaml file to inc Modbus and modbus.yaml file example below:- 

# Loads default set of integrations. Do not remove.
default_config:

# Load frontend themes from the themes folder
frontend:
  themes: !include_dir_merge_named themes

automation: !include automations.yaml
script: !include scripts.yaml
scene: !include scenes.yaml
template: !include template.yaml
modbus: !include modbus2.yaml
media_player:

