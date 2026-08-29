# DaybyDay 隱私政策

DaybyDay（孕期與育兒記錄 app）的隱私政策公開頁。

- 網址：<https://jackintheboxxx.github.io/daybyday-privacy/>
- App bundle ID：`com.roundone.daybyday`

## 不要手改 index.html

這一頁由 app 內的 `src/data/legalData.js` 產生，指令：

```bash
node tools/gen_privacy.js
```

app 內顯示的政策全文與這一頁同源，所以永遠一致。
直接改 HTML 會令兩邊分歧 —— Apple 審核時會比對 app 內與網頁版。
