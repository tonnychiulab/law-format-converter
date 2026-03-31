# 法規格式轉換器

🚀 自動將法規檔案轉換為 AnythingLLM 格式

## ✨ 功能

- ✅ **支援 PDF 直接上傳** - 自動提取文字
- ✅ **多格式輸出** - TXT、Markdown、JSON
- ✅ **自動識別法條結構** - 智能解析法規格式
- ✅ **實時預覽** - 轉換前檢視結果
- ✅ **100% 隱私安全** - 全在瀏覽器執行，不上傳任何資料

## 🎯 使用場景

- 將全國法規資料庫的 PDF 轉成 AnythingLLM 格式
- 快速準備法規訓練資料
- 無需 IT 幫忙，自助化轉換

## 🚀 立即使用

訪問：https://law-format-converter.pages.dev/

### 使用步驟

1. **上傳檔案**
   - PDF（自動提取文字）
   - TXT、Markdown、JSON

2. **選擇格式**
   - TXT（推薦）
   - Markdown
   - JSON

3. **轉換**
   - 點「開始轉換」
   - 自動識別法條結構

4. **下載**
   - 預覽檢查
   - 點「下載檔案」

5. **上傳到 AnythingLLM**
   - 登入 AnythingLLM
   - 進入 Documents
   - 上傳檔案
   - 完成！

## 📊 支援的格式

### 輸入格式
- ✅ PDF（文字版）
- ✅ TXT（純文字）
- ✅ Markdown（.md）
- ✅ JSON / JSONL

### 輸出格式
- 📄 **TXT** - 純文字，AnythingLLM 最友善
- 📝 **Markdown** - 結構化標記
- 🔧 **JSON** - 機器可讀

## ⚠️ 已知限制

- 掃描版 PDF（圖片）無法直接提取，需先用 OCR 轉換
- 推薦用 [ilovepdf.com](https://ilovepdf.com) 的「提取文字」功能

## 🔒 隱私說明

✅ **完全隱私安全**
- 所有檔案處理都在你的瀏覽器執行
- 沒有任何資料上傳到伺服器
- 沒有 Cookie、追蹤或分析
- 完全開源，可以審查代碼

## 💡 技術細節

- 純 HTML + JavaScript
- 使用 [PDF.js](https://mozilla.github.io/pdf.js/) 提取 PDF 文字
- 部署在 Cloudflare Pages（免費 CDN）
- 支援所有現代瀏覽器（Chrome, Firefox, Safari, Edge）

## 🤝 反饋和改進

遇到問題？有改進建議？
- 在 GitHub 上提 Issue
- 或聯絡開發團隊

## 📝 授權

MIT License - 自由使用和修改

## 🔗 相關資源

- [AnythingLLM 文檔](https://docs.anythingllm.com/)
- [全國法規資料庫](https://law.moj.gov.tw/)
- [PDF.js 文檔](https://mozilla.github.io/pdf.js/)

---

**快速開始**

```bash
# Clone repo
git clone https://github.com/[你的帳號]/law-format-converter.git
cd law-format-converter

# 本機測試（用 Python 簡單伺服器）
python3 -m http.server 8000

# 訪問 http://localhost:8000
```

---

## 部署到 Cloudflare Pages

### 前置準備
1. GitHub 帳號
2. Cloudflare 帳號（免費）

### 部署步驟

1. **Fork 或 Clone 本 Repo**
   ```bash
   git clone https://github.com/[你的帳號]/law-format-converter.git
   ```

2. **上傳到你的 GitHub**
   ```bash
   cd law-format-converter
   git push
   ```

3. **連接到 Cloudflare Pages**
   - 訪問 https://pages.cloudflare.com
   - 點「Create a project」→「Connect to Git」
   - 選擇 `law-format-converter` repo
   - 點「Deploy」

4. **等待部署完成**
   - 通常 1-2 分鐘
   - 檢查部署狀態

5. **訪問你的網站**
   - https://[repo-name].pages.dev

### 自訂網址（可選）

在 Cloudflare Pages 中設定自訂域名：
```
例如：https://law-converter.yourdomain.com
```

---

## 常見問題

### Q: 資料安全嗎？
A: 100% 安全。所有處理都在你的瀏覽器執行，沒有任何資料上傳。

### Q: 支援多大的檔案？
A: 支援到 100+ MB（瀏覽器記憶體限制）。通常法規檔案 < 10MB，完全沒問題。

### Q: PDF 轉換不了怎麼辦？
A: 可能是掃描版 PDF。用 [ilovepdf.com](https://ilovepdf.com) 先「提取文字」，再用本工具。

### Q: 可以離線使用嗎？
A: 可以。下載 `index.html`，在本機瀏覽器打開即可。

### Q: 支援中文嗎？
A: 完全支援繁體中文和簡體中文。

### Q: 有費用嗎？
A: 完全免費。Cloudflare Pages 和 GitHub 都免費。

---

## 更新日誌

### v1.0 (2026-03-31)
- ✅ 首次發布
- ✅ 支援 PDF 直接上傳
- ✅ 支援 TXT/MD/JSON 轉換
- ✅ 實時預覽功能
- ✅ Cloudflare Pages 部署

---

**享受使用！** 🎉

有任何問題，歡迎反饋。
