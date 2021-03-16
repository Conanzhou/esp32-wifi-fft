# Wifi SCAN and FFT

scan for available set of APs.
    * 初始化时判断FLASH中是否存有有效的路由器参数(esp_wifi_get_config)
    * 已存有路由器参数，去搜索看看AP当前是否存在(esp_wifi_scan_start)
    * 不存在连接后再保存参数esp_wifi_set_config
    * 周期性检测AP连接状态？
connect to the chosen one.
get the FFT parameter from severs.
print out the output of FFT.
