# 長洲海濱夾公仔

原創 16:9 網頁 mini game。每局扣除 200 分，玩家可按住左右按鈕移動夾爪，再按「落爪」嘗試抓取長洲主題公仔。

## 本機預覽

以任何靜態 HTTP server 開啟此資料夾的 `index.html`。遊戲支援 `?score=1000`，並沿用主遊戲的 `island-stats` postMessage 格式：

- 輸入／輸出：`score`
- 收藏資料：`clawPrizes`
- 返回故事：`complete: true`

## 設定

`config.json` 可修改遊戲費用、單機起始分數、移動速度、抓取範圍、公仔名稱與抓取成功率。

背景圖由 OpenAI 內置 ImageGen 產生，最終 prompt 為「長洲海濱懷舊嘉年華黃昏場景，深藍綠與暖琥珀色調，中央留空予遊戲機台，無文字、標誌、水印或前景人物」。
