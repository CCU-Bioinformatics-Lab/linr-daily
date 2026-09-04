<!-- daily-log:generated — 這個檔由 render.py 產生，手改會被覆蓋 -->
# 每日工作日誌

## 怎麼看

日誌是 **HTML**（排版完整，含配色、圖表、折疊區）。
⚠️ **GitHub 網頁點 `.html` 只會顯示原始碼**，要先把檔案取下來：

```bash
git clone https://github.com/CCU-Bioinformatics-Lab/linr-daily.git
cd linr-daily && xdg-open index.html      # macOS 用 open，Windows 用 start
```

或按 **Code → Download ZIP**，解壓後點 `index.html`。

下面的索引供快速定位哪一天發生什麼；點進去要用上面的方式開。

> **給 agent**：要跨日彙整（「掃過這個月的紀錄，整理出進度」）請直接讀
> `.data/<日期>.json` —— 那是事實來源，欄位有語意、不必剖 HTML。

## 檔案結構

| 路徑 | 說明 |
|---|---|
| `.data/<YYYY-MM-DD>.json` | **事實來源**。要改內容改這裡再重新渲染 |
| `daily/<YYYY-MM-DD>.html` | 單日日誌（產物，不要手改） |
| `index.html` | 導覽首頁（產物） |
| `README.md` | 本檔（產物，由 `render.py` 產生，不要手改） |
| `daily/figures/<YYYY-MM-DD>/` | 當天的圖 |
| `assets/style.css` | 共用樣式，改這裡會影響所有 HTML 日誌 |

## 日誌

### 2026-09

- **[2026-09-05](daily/2026-09-05.html)** —— 引用之前先複驗：PyClone 的數字全對得上，LICHeE 的原始碼有兩處對不上論文、還有三個論文沒提的行為；實驗室 16 個 repo 也讀成一份可查的地圖，其中一個專案跟我的題目落在同一個問題域
- **[2026-09-04](daily/2026-09-04.html)** —— PyClone 從正文讀到附錄：先前三條說法撤回，論文六項數值宣稱有兩項用原始資料重現不出來；日誌與週報也接成每週三晚上自動產出的管線
- **[2026-09-03](daily/2026-09-03.html)** —— 簡報進入定稿期：目標函數的質疑獨立成 P0.5 專頁、全份改成 15 頁圖說版；先前兩條結論一條撤下、一條下修
