# 台灣上市+上櫃公司 月營收成長率計算器（已設定 Proxy）

## 功能
- 輸入股票代號、年份、月份，自動抓取 MOPS 月營收資料
- 計算：
  - 當月 vs 去年同期成長率
  - 當月 vs 上月成長率
  - 累計 vs 去年同期累計成長率
- 顯示公式

## 部署方法
1. 此版本已內建 Cloudflare Worker Proxy： `https://misty-star-5347.l9000003216.workers.dev/`
2. 將 `index.html` 上傳到 GitHub Repository。
3. 啟用 GitHub Pages，即可使用。

## 資料來源
- 上市公司：`https://mops.twse.com.tw/nas/t21/sii/`
- 上櫃公司：`https://mops.twse.com.tw/nas/t21/otc/`
