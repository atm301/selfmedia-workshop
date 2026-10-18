# 自媒體經營開發陌生客戶｜學員站

講師 何佳勳（小圭）／圭話行銷；2026/10/19，3 小時下午場（10/02 首場在台中，10/19 這場沿用同一個網址）。單頁 HTML、GitHub Pages。

- **index.html**：組別（1 到 8 組）＋暱稱報到、8 分頁、5 題加分題（投完顯示解答）、內容矩陣填寫器、遊戲化活動企劃表、全班投票（每人 2 票不能投自己）、9 張提示詞一鍵複製、30 個工具連結、四個實作上傳、21 天行動計畫。
- **admin.html**：後台（noindex）上傳牆／計分／加分題／發表投票／學員，可匯出 CSV。

後端：共用 Supabase `lw_line_students`（course=`selfmedia-workshop`）＋ `lw_workshop_submissions` ＋ `lw_workshop_scores` ＋ `lw-workshop` bucket。
