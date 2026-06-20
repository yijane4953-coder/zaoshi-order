# 灶囍手作訂購管理系統

傳統市場攤商用的輕量訂單管理系統。客人線上下單，店家用後台管理訂單、付款與出貨狀態。

> 目前版本：v1.6.4　最後更新：2026/06/20

---

## 線上網址

- 前台（客人訂購）：`https://mumuworks.github.io/zaoshi-order/`
- 後台（店家管理）：`https://mumuworks.github.io/zaoshi-order/admin.html`

## 技術架構

- 前端：純 HTML / CSS / JavaScript（無框架）
- 後端：Google Apps Script（Web App）
- 資料庫：Google Sheets
- 部署：GitHub Pages（免費）

詳細架構請見 `TECH_ARCH.md`。

## 主要功能

- 套餐／單點商品線上訂購，三種取貨方式（自取／低溫宅配／7-11店到店）
- 依商品實際重量分件計算運費（宅配每件20kg、7-11每件10kg，滿$3,000免運）
- 訂單確認、配達日期填寫、後台訂單管理與篩選
- 後台備貨統計、營收統計、不可取日控制

## 開發分支策略

- `main`：正式版本，GitHub Pages 由此部署
- `develop`：開發測試分支，新功能先在此驗證，確認無誤後以 Pull Request 併入 `main`

詳細版本紀錄請見 `CHANGELOG.md`；後續開發規劃請見 `ROADMAP.md`。

## 文件索引

| 文件 | 內容 |
|---|---|
| `PRODUCT_SPEC.md` | 產品規格、商品定義、欄位驗證規則 |
| `CHANGELOG.md` | 版本更新紀錄 |
| `ROADMAP.md` | 版本狀態總覽與後續規劃 |
| `TECH_ARCH.md` | 技術架構、API 端點、檔案結構 |
| `DATABASE.md` | Google Sheet 欄位結構說明 |
