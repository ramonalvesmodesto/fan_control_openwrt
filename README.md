``` bash
wget https://raw.githubusercontent.com/ramonalvesmodesto/fan_control_openwrt/main/fa-fancontrol.sh -O /usr/bin/fa-fancontrol.sh
wget https://raw.githubusercontent.com/ramonalvesmodesto/fan_control_openwrt/main/fa-fancontrol-direct.sh -O /usr/bin/fa-fancontrol-direct.sh
wget https://raw.githubusercontent.com/ramonalvesmodesto/fan_control_openwrt/main/fa-fancontrol -O /etc/init.d/fa-fancontrol
 
chmod +x /etc/init.d/fa-fancontrol
chmod +x /usr/bin/fa-fancontrol.sh
chmod +x /usr/bin/fa-fancontrol-direct.sh
 
service fa-fancontrol enable
service fa-fancontrol start
```
