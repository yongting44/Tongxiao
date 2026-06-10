# 雲端上的通霄

D2C 與 OMO 地方創生電子商務藍圖互動式網頁。

## 使用方式

1. 將本資料夾內容上傳到 GitHub Repository。
2. 確認首頁檔名為 `index.html`。
3. 到 GitHub Repository 的 **Settings → Pages**。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選擇 `main` / root。
6. 等待部署完成後即可開啟 GitHub Pages 網址。

## 注意事項

- 本專案使用 CDN 載入 Tailwind CSS、Chart.js、Lucide Icons 與 Google Fonts，因此需要網路連線。
- Gemini API Key 為選填。未填寫時，AI 功能會以模擬回覆運作，不會造成按鈕失效。
- 會員中心 Modal 已修正為關閉時 `hidden`，避免透明遮罩蓋住頁面導致連結無法點擊。
