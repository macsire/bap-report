# Benzo[a]pyrene Report

This is a topic-based website about benzo[a]pyrene (BaP), food safety, industry self-management, and the public disclosure of environmental monitoring data. It focuses on the need for more complete and traceable inspection and monitoring information beyond product batch lookup, providing background context for understanding food contamination risks.
這是一個關於苯駢芘（BaP）與食品安全、業者自主管理、環境監測公開資料的專題網頁。內容聚焦於產品批號查詢之外，台灣社會仍需要更完整、可追溯的檢驗與監測資訊，作為理解食品污染風險的背景參考。
頁面結構 / Site structure
	•	index.html　首頁：專題引言、查證原則、三大部分入口
	•	food.html　食品端：苯駢芘是什麼？為什麼會出現在食品裡？
	•	environment.html　環境端：BaP 是代表指標，環境中還有 PAHs 家族
	•	oversight.html　監管端：台灣工業區環境監測與監管責任
	•	summary.html　總結：出事查批號求自保　食安治本需要落實監測
- `styles.css`　全站共用樣式
- `assets/`　三張說明圖卡（SVG）與內嵌字型

## 版本紀錄 / Version history


**v0.5**
內容修正：
	•	JECFA 建議以 BaP 作為 PAHs 監測指標之年份，由 2006 年修正為 2005 年
	•	PAH4 中 BbF（benzo[b]fluoranthene）化學名稱，依環境部 NIEA 標準名稱修正為「苯駢[b]螢蒽」
	•	監管端工業區監測數據表格欄位調整為「工業區／111–113 年 BaP 年均濃度／說明」三欄
	•	食品端「吃到苯駢芘對身體有什麼影響？」段落擴充為短期／中期／長期三階段說明，並補充 EPA 口服致癌斜率因子（cancer slope factor）數據
	•	總結頁資料來源清單新增 WHO／JECFA 資料庫、PMC 生物標記研究、US EPA IRIS 三筆連結
	•	修正數處標點與中英文間距問題
  
**v0.4**
- 文案全面改寫為面向大眾的公開版本，移除企劃／設計備註等內部溝通用語
- 修正 v0.3 遺留的導覽列壞連結
- 部分段落標題改為兩行式呈現與圖卡視覺節奏對齊
- 三張圖卡（card-01／02／03）沿用 v0.3 原始 SVG，內容與位置不變

**v0.3**
- 五頁式網站初版：首頁＋三部分內文＋總結，含各國食品端／環境端 BaP、PAHs 管理比較
- 建立共用 `styles.css` 與三張圖卡視覺

