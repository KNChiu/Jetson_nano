### 2019/12/09

## 風扇設定(Fan)
   * ech0 (255 - 0)
   ```
   sudo sh -c ‘echo 255 > /sys/devices/pwm-fan/target_pwm’
   ```
   
## 網路設定
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
   * 使用 ssh 連線同網域設備
   ```
   ssh <帳號>@<ip位址>
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

## Git 控管
   * 取得git文件
   ```
   git clone <網址>
   ```
   * 更新git文件
   ```
   git pull
   ```
   * 重整git文件
   ```
   git reset
   ```


## 資源監控
   * 安裝 jtop 套件
   ```
   sudo pip install jetson_stats
   ```
   * 開啟
   ```
   sudo jtop
   ```
   
