# WooCommerce 8.9.x
提供購物車 WooCommerce 金流模組, 可以較快速的方式介接SYSPAY金流系統。

目錄
-----------------
* [開發版本](#開發版本)
* [安裝](#安裝)
* [設定](#設定)
    1. [主要設定](#主要設定)
    2. [金流設定](#金流設定)
    3. [注意事項](#注意事項)
* [技術支援](#技術支援)




開發版本
-----------------
<img src="https://img.shields.io/badge/Now--Scott-6.7.1-red?label=WordPress&labelColor=blue"> <img src="https://img.shields.io/badge/Now--Scott-8.9.3-red?label=WooCommerce&labelColor=blue"> <img src="https://img.shields.io/badge/Now--Scott-8.2-red?label=PHP&labelColor=blue">



安裝
-----------------
1 下載檔案 -> 解壓縮檔案

2 WordPress後台 -> 外掛 -> 安裝外掛 -> 上傳 -> syspay-ecommerce-for-woocommerce.zip -> 立即安裝 -> 啟用外掛


設定
-----------------

##### 主要設定
-----------------
- 您可在此勾選啟用精誠金融金流。

1 `WordPress後台` -> `WooCommerce` -> `設定(Settings)` -> `精誠金融科技(頁簽)` -> `主要設定(頁簽)` -> `啟用精誠金融金流` -> 勾選

2 模式 -> `啟用測試模式`，請確認是用測試環境的測試資訊 -> 勾選，否則請取消勾選

3 `儲存變更`

##### 金流設定
-----------------
- 您可在此輸入精誠金融API串接資訊，請至SYSPAY店家後台查看，若啟用測試模式，測試資訊請直接在測試環境申請或跟金流顧問索取。

1 商店代號 -> `SYSPAY店家後台` -> `系統管理` -> `系統介接設定` -> `商店代號`

2 HashKey -> `SYSPAY店家後台` -> `系統管理` -> `系統介接設定` -> `介接 HashKey`

3 HashIV -> `SYSPAY店家後台` -> `系統管理` -> `系統介接設定` -> `介接 HashIV`

4 `儲存變更`

##### 注意事項
-----------------
- 是否啟用管理庫存設定，若是啟用，當超過設定時間後未付款，再點選該筆訂單後，將自動取消該筆訂單。信用卡預設60分鐘，ATM虛擬帳號預設3天，若使用者自訂的保留時間大於預設時間，則使用此設定的時間。

1 `WordPress後台` -> `WooCommerce` -> `產品(Products)(頁簽)` -> `存貨(Inventory)(頁簽)` -> `管理庫存(Manage stock)` -> `啟用庫存管理` -> 勾選

2 `持有庫存(分鐘)` -> 輸入分鐘數

3 `儲存變更`


技術支援
-----------------
技術客服信箱：syspaysupport@systexfintech.com




