WorkerQuota

# 用途

測試並驗證移工管理系統的需求

# 安裝

將 [WorkerQuota.zip](https://github.com/forwardhrm/public/raw/master/WorkerQuota/WorkerQuota.zip) 解壓縮至一個單獨目錄，然後執行其中的 WorkerQuota.exe 即可。

如果 Windows 環境上面缺少 .NET 函式庫，應該會出現提示訊息。只要按照提示訊息來下載和安裝 .NET 6.0 即可。

# 用法

1. 從聘軒系統匯出「日期別移工入境總覽表(xls版)」檔案，然後用 Excel 開啟該檔案，並且另存為「Excel 活頁簿 (*.xslx)」格式的檔案。

註：聘軒系統匯出的 .XLS 檔案是一種稱為「XML 試算表 2003」的老舊格式，不利於後續處理，所以需要先用 Excel 另存為較新的 .XSLX 格式。

2. 執行 WorkerQuota.exe，然後按照下圖的指示操作：

![](WorkerQuota.jpg)

說明：

(1) 點一下［瀏覽］按鈕，然後選擇上述步驟 1 所產生的 .XSLX 檔案。

(2) 選擇雇主（客戶），然後點［尚可增聘多少人？］按鈕，程式便會讀取境後相關表與勞保人數調查表，並計算該名客戶還能增聘幾名移工。

註：右邊的「提示訊息」視窗是用來顯示程式執行過程中發現的問題或詳細資訊，主要是用來除錯。
