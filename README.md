# Crypto AI・SNR 手機 App（PWA）

這是可安裝到 iPhone 主畫面的漸進式網頁 App 套件，不是已上架 App Store 的原生 iOS App。

## 部署與安裝
1. 將資料夾內全部檔案上傳到支援 HTTPS 的靜態網站主機。
2. 確保 index.html、manifest.webmanifest、sw.js 和 icons/ 位於同一網站目錄。
3. 用 iPhone Safari 開啟 HTTPS 網址。
4. 點分享 →「加入主畫面」→「加入」。

## 功能與限制
讀取 Binance USDⓈ-M Futures 公開 K 線，計算 SNR、RSI、EMA、MACD、ATR 和風險試算。
不會自動下單、不需要交易所 API Key。即時行情需要網路。這是規則式技術訊號原型，不是經訓練的機器學習模型，也不保證獲利。
