# 115 年度進階小兒學術研討會｜學員專區

單一檔案網頁：`index.html`。所有會變的內容都在 `<script>` 最上方的「設定區」：

- `LINKS`：前測作答表單、滿意度問卷、講義連結（空字串會顯示「連結準備中」）
- `PRETEST_QUESTIONS`：前測題目（只放題目，不放答案）
- `SCHEDULE`：課程表
- `WORKSHOP`：週日分組練習的站別與分組名單（只含學會編號與姓名）
- `FOOD`：午餐地圖的店家

改完推到 `main`，Netlify 會自動重新部署。給學員的網址請加上 `?openExternalBrowser=1`，從 LINE 點開會直接用手機瀏覽器開啟。
