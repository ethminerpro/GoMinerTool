# minerProxy
已內置加密證書，可以自定義ssl證書，在程序目錄下放入server.key和server.pem文件即可；

交流電報群https://t.me/trexminerproxy

開發費恒定千三！無論你抽3%還是30%，甚至80%，都是0.3%開發費！
支持ETC轉發！


# 更新日誌
```bigquery
2022-05-01 01:00    2.2.0 >>> 51國際勞動節快樂！(強烈建議老版本更新)
2022-04-30 01:00    2.1.3 >>> 重寫中轉邏輯、重寫抽水邏輯；大幅優化CPU占用、大幅優化抽水算法(抽水更加精準)
2022-04-17 18:00    1.5.2 >>> 優化抽水邏輯，抽水更平穩
2022-04-14 18:00    1.5.1 >>> 優化中轉性能、優化內存占用、優化小算力礦機抽水比例
2022-04-08 18:00    1.5.0 >>> 優化抽水算法、優化控製臺日誌打印、提升性能
2022-04-05 17:00    1.4.2 >>> 修復某些情況下代理抽水異常的BUG、優化邏輯，提升性能
2022-03-30 16:00    1.3.0 >>> 增加服務硬件信息概況、增加礦池延時信息、優化界面、提升性能
2022-03-25 16:00    1.2.0 >>> 增強安全性、增加ETC幣種、優化圖表展示、性能優化
2022-03-24 17:00    1.1.1 >>> 優化折線圖、優化數據展示、優化礦機列表
2022-03-22 23:00    1.1.0 >>> 修復：抽水礦機名問題，曲線圖展示問題，端口列表裏面顯示離線設備數量
2022-03-15 19:00    1.0.0 >>> 第一個版本發布
```
# windows版本下載:
點擊左側Code，然後選Download ZIP即可；

解壓縮後復製到服務器，
運行「win服務器守護」！ 



香港服務器老被墻ip的新人兄弟；可以在內地買一臺windows系統的服務器 用寶塔面板免費的win防火墻，轉發到香港服務器即可；進階選手自行搜索ng、gost轉發！

# 新增linux一件腳本安裝
```
bash <( curl -s -L https://raw.githubusercontent.com/ethminerpro/MinerProxy/main/install.sh )
```


## 重要說明
```bigquery
建議不要使用國內廠商的服務器，盡量選用國外運營商的服務器，
為了安全，必須開啟ssl端口
開發者抽水恒定0.3%！！目前運行最穩定的軟件；歡迎實測！
不建議抽太多，做到可持續發展，托管時請一定告知客戶存在托管費

```

# 如果你算力不準：
①第一檢查挖礦軟件配置及內核配置，是否設置超過多少分鐘沒有成功提交重啟內核

②查看你服務器的硬件配置及軟件帶寬，配置過低可能導致轉發性能不足，導致重發及超時

③檢查你服務器的網絡是否占用超過60%以上，是的話加帶寬
