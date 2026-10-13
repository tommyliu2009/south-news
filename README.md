# 南部地方新聞網

網址：https://web13.subsidyking.tw/（備用 https://tommyliu2009.github.io/south-news/）

每日彙整嘉義市、嘉義縣、臺南市、高雄市、屏東縣、花蓮縣、臺東縣、澎湖縣、金門縣、連江縣政府新聞稿，涵蓋政策、補助、標案與預算，提供摘要與原始連結。

## 更新方式
本站與其他五站共用一支更新腳本（每天 4:32 由排程執行）：

- 腳本路徑：`/workspace/localnews/update_all.py`
- 一次更新六站並部署：`python3 /workspace/localnews/update_all.py`
- 只更新本站：`python3 /workspace/localnews/update_all.py 30 --only south-news`
- 只產生不推送：加 `--no-push`
- 報告：`/workspace/reports/localnews_YYYYMMDD.md`

分類：政策、補助、標案、預算、綜合新聞。摘要附原文連結，不轉載全文。
廣告：仁禾管理顧問／劉靜渡／tommyliu2009@gmail.com／LINE ID：tommyliu2009
