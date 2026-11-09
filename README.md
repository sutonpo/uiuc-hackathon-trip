# Illinois Field Notes

UIUC 精準與數位農業黑客松旅行頁面，2026/11/10–18。

直接用瀏覽器開啟 `index.html`。不需安裝套件；樣式與互動均在單一檔案中，離線也可查看。外部導航與官方網站需網路。勾選與備忘只存在同一瀏覽器。

## GitHub Pages

將此資料夾內容放入指定 GitHub repository。在 repository 的 Settings → Pages 選擇 Deploy from a branch，分支選 main、資料夾選 /(root)，儲存後等待部署。可用性及公開範圍依 GitHub 帳號／方案設定；發布前核對此行程的可見性。

目標 repository：sutonpo/uiuc-hackathon-trip。網站由 main 分支根目錄發布。

## 資料狀態

- 航班來自使用者提供的 Trip.com 文件，並非即時航班狀態。
- 11/10、11/11 HI Chicago；11/12–15 香檳附近希爾頓依使用者訊息。希爾頓分店與最後一晚待確認。
- 火車為官方公布時刻參考，非指定日期的已訂車票。
- 11/15 回芝加哥與當晚住宿為建議，未視為已訂。
- 活動議程為主辦方暫定版本，時區標註有不一致之處，應向主辦方核對。
- 已排除姓名、生日、電話、電子郵件、訂單編號、訂位代碼及原始 PDF。

內容修改：在 `index.html` 的 `plan` 陣列調整每日安排；住宿和交通卡片在對應 HTML 區塊。

## 地圖與交通

使用 Google Maps 內嵌地圖及跨平台導航連結；載入地圖和交通查詢需要網路。提供 Amtrak 訂票、Train Status 入口、Illini 官方時刻表、CTA 班表與車站導航。沒有接入即時票價或車票訂單。
