### 2019/12/09

## jeton nano fan
   * ech0 (255 - 0)
   ```
   sudo sh -c ‘echo 255 > /sys/devices/pwm-fan/target_pwm’
   ```
## jetson nano wifi
   * 列出可用wifi     
   ```
   sudo nmcli device wifi list
   ```
   * 連上指定wifi 
   ```
   sudo nmcli device wifi connect <ssid_name> password <password>
   ```
 
