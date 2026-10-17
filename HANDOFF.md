# Handoff — P026 跳石陣舊占位倉庫（Jumpstone Reference）

- 更新時間：2026-10-18T03:25+08:00
- 更新者：Claude（核對倉庫歷史，撰寫交接）
- 倉庫：https://github.com/jackeytw886/install-jumpstone-reference（舊名 Jump-again，GitHub 會自動轉址）
- 分支：main
- 本次基準 SHA：`13448c2dcede4eb69b506bd778338c53862fb5de`（Codex 管理整理提交）
- 核對層級：已讀完整 Git 歷史與所有檔案。

## 1. 現況

這個倉庫**沒有任何程式或素材**。Git 歷史只有兩筆：

| 提交 | 時間 | 內容 |
| --- | --- | --- |
| `9284686` | 2026-05-16 08:04:34 | Initial commit：只有 README.md，內容是「# Jump-again／由 EZPage 建立的網站 - Deployed by EZPage」 |
| `13448c2` | 2026-10-17 | Codex 管理整理：加上 AI 入口與管理文件，改名為 install-jumpstone-reference |

沒有 `index.html`，也沒有啟用 GitHub Pages。

## 2. 推測的來由（未證實）

同一天早上用 EZPage 建立的倉庫依序是：

| 時間 | 倉庫 | 結果 |
| --- | --- | --- |
| 08:02:50 | `-`（P027，現名 legacy-site-placeholder） | 只有 README，沒有網頁 |
| 08:04:34 | **Jump-again（本倉庫）** | 只有 README，沒有網頁 |
| 08:05:03 | Champagne（P009，穿越跳石陣 v3.5） | 3 秒後上傳 `index.html`，部署成功 |

EZPage 的正常流程是「Initial commit」後幾秒內接著「更新 index.html via EZPage」。本倉庫只有第一步，名稱又是「Jump-again」（再跳一次），因此**很可能是部署「穿越跳石陣」時中途失敗的一次嘗試**，之後改用 Champagne 名稱重新部署成功。這是依時間順序的推測，需作者確認。

## 3. 相關專案

- P009 Champagne：穿越跳石陣 v3.5 環形燈條版（實際網頁）。
- P010 Melody：穿越跳石陣 v3.8 猜旋律版。
- 實體版韌體（Arduino Mega 30 通道）不在任何已登記的倉庫中。

## 4. 建議處置（需作者決定，AI 不要自行執行）

1. **封存（Archive）**：若確認沒有任何連結或 QR code 指向它，可在 GitHub 設定中封存，保留代號 P026。
2. **改作跳石陣實體資料倉庫**：把 Arduino 韌體（如 `jumpstone_single_mega_30ch_v2.ino`）、接線圖、CF9510M 音檔清單放進來，成為 P009／P010 的硬體端。
3. **維持現狀**：不影響其他專案。

## 版本定位

基準 SHA 定位本次文件修改前的倉庫內容；本次文件提交由此檔所在的 Git 提交與倉庫歷史定位，不預填同一提交自己的 SHA。
