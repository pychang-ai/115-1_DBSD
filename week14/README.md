# 第 14 週｜AJAX、JSON 與 REST API（2026/12/10）

- 對應教科書：Ch14 AJAX／JSON 與 REST API
- 教學內容：
  - 14-1 AJAX、14-3 PHP 與 JSON、14-5 建立 REST API
  - 【測試主題 8】API 與整合測試：用 curl／VS Code REST Client 打自己的 JSON API，檢查狀態碼與欄位

## 隨堂作業

作業W14：做一支回傳 JSON 的查詢 API，用 curl 打它並截圖驗證回傳

- 第 3 節上機時完成，貼到當週 Canva 答題卡自己學號末兩碼的卡片，下課前完成

## 作業W14 學習單（1 題）

**題目**：做一支 `api.php`：接收船型參數，回傳該船型資料的 JSON（`header("Content-Type: application/json")`）。**測試主題 8**：用 `curl "http://localhost/api.php?type=貨櫃"` 打它，檢查回傳是合法 JSON 且欄位正確。

**資料**：自己的 ships 資料表。

**繳交物**：curl 執行畫面截圖（看得到 JSON 回傳）。

**評分要點（Pass／Fail）**：API 回傳合法 JSON；curl 測試有做且欄位對。
