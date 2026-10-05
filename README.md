# Sanctuary Aegis • GitHub Pages Deployment Guide

這個資料夾 (`docs/`) 包含了 **Sanctuary Aegis (庇護之盾)** 專案的官方展示主頁 (`index.html`) 與法定隱私權政策 (`privacy.html`)。

已完全符合：
1. **Apple App Store Review Guidelines 5.1.1**（隱私權政策必備 URL）
2. **HIPAA / GDPR Zero-Knowledge 規範**
3. **加州刑法 § 632 / 佛州法典 § 934.03 雙方通訊監察同意規範**
4. **FDA 21 CFR 860 / Apple 1.4.1 非自律醫療診斷免責宣告**

---

## 🚀 如何在 GitHub 上傳並啟用 GitHub Pages (30 秒)

### 步驟一：將程式碼或此 `docs` 資料夾推送到你的 GitHub Repository
在終端機執行：
```bash
git add docs/
git commit -m "feat: add Sanctuary Aegis showcase and zero-knowledge privacy policy"
git push origin main
```

### 步驟二：在 GitHub 開啟免費託管 (GitHub Pages)
1. 開啟您的 GitHub 專案頁面：`https://github.com/howly7777777-svg/sanctuaryaegis`
2. 點擊頂部 **Settings**（設定）
3. 在左側選單點擊 **Pages**
4. 在 **Build and deployment** 下方的 **Branch**：
   - 選擇分支：`main`
   - 選擇資料夾：`/ (root)` 或 `/docs`
5. 點擊 **Save**（儲存）

### 步驟三：取得 App Store Connect 上架所需填寫資料
- **官方首頁與技術支援 (Support & Marketing URL)**：  
  `https://howly7777777-svg.github.io/sanctuaryaegis/index.html`
- **法定隱私權政策 (Privacy Policy URL)**：  
  `https://howly7777777-svg.github.io/sanctuaryaegis/privacy.html`
- **官方客服與審核諮詢郵件 (Support Email)**：  
  `howly7777777@gmail.com`

> 將上述網址與信箱填入 App Store Connect 的「隱私權政策網址」、「支援 URL」與「聯絡資訊」欄位即可完全符合 Apple 審查規範！
