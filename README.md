壹、系統目的
===
本次專案採訪的商家，目前營運模式大多是以人工為主，無論是每日記帳、結帳、進貨等等，以及商品的細項資訊，皆是以人力的方式進行紀錄及判斷，目前的客源量也大多來自於熟客，較無新進不同客源，也無其他銷售通路，以實體店面現存為主，尚無任何資訊系統之使用。

此系統建構一個協助營運之資訊系統，具備以下功能，取代原有之紙本作業，以達成減少人力開支及增進整體營運效率之目的。

一、數量管理
---
透過對於進貨、銷售、存貨之數值控管，達到對使用量的實際掌握度，透過系統紀錄之數量，統計出各項商品的使用量，每次紀錄也會同時更新現有量，查詢的準確度也將提升，對於各項商品是否需進貨及進貨數量的確認也更加便利，以此達到取代現有之紙本作業。
二、庫存保鮮
---
因部分商品為食品且具有食用效期，當數量過多時，以人工紀錄及查詢會有一定的困難，透過這個系統，彙整現存所有商品之各項資訊，品名、進貨日期、即期商品之售價等等，且在查詢哪些商品即將到期時也更加迅速，以此更能夠避免有到期商品仍在架上的問題產生。
三、財務管理 
---
對店家營運期間內所有產生之交易，如買進的貨物、賣出的商品、刷卡金額或是其餘設備及人力之開銷，皆儲存到本系統中，以此紀錄每日開支，最終彙整為每月結算，讓店家對於金流的控管更加一目了然。

參、開發環境
===
一、Visual Basic
---
  是由微軟公司開發的包含環境的事件驅動程式語言，我們使用此程式語言，撰寫系統介面以及設計。
二、phpMyAdmin
---
  是架構在網站主機上的 MySQL 的資料庫管理工具，我們使用此工具建置資料庫。
三、MySQL Azure 資料庫
---
  用上面的 phpMyAdmin 工具建置好的資料庫，匯出其 sql 檔案，匯入到 MySQL Azure資料庫，讓小組成員可以在不同地方連接資料庫，且即時更新至雲端資料庫。
