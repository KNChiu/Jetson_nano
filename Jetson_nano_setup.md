### 2019/12/09

## 風扇設定(Fan)
   * ech0 (255 - 0)
   ```
   sudo sh -c ‘echo 255 > /sys/devices/pwm-fan/target_pwm’
   ```
   
## 網路設定(wifi)
   * 列出可用wifi     
   ```
   sudo nmcli device wifi list
   ```
   * 連上指定wifi 
   ```
   sudo nmcli device wifi connect <ssid_name> password <password>
   ```
   * 有線連線(USB)
   ```
   IP : 192.168.55.1
   ```
   
## 電源設定
   * 模式檢查
   ```
   sudo nvpmodel -q
   ```
   * 低耗電模式(5W)
   ```
   sudo nvpmodel -m1
   ```
   * 高效能模式(10W)
   ```
   sudo nvpmodel -m0
   ```
