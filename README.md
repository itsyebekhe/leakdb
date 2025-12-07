# 👻 Banking OSINT Tool
### موتور جستجوی داده‌های بانکی (Melli & Mellat)

**GHOST** is a serverless frontend interface designed to query the `yebekhe/bdata` dataset hosted on Hugging Face. It utilizes the **Datasets Server API** to perform SQL-like queries on Parquet files without requiring the user to download the massive database.

![Status](https://img.shields.io/badge/Status-Online-green)
![Database](https://img.shields.io/badge/Database-HuggingFace-yellow)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20DuckDB-blue)

---

## 🚀 Features (امکانات)

*   **🔍 Smart Omni-Search:** Single input field that auto-detects:
    *   **National Code:** 10-digit validation.
    *   **Mobile Number:** 09xx format detection.
    *   **Name:** Persian text normalization.
*   **⚡ Zero-Download:** Search through millions of records instantly via API. No need to download 2GB+ files.
*   **📱 Mobile Optimized:** Responsive Bento-grid design with touch-friendly tables.
*   **🏦 Bank Detection:** Automatically identifies and badges results for **Bank Mellat** vs **Bank Melli**.
*   **🛠️ Tools:** JSON Export, Clipboard Copy, and Client-side Sorting.

---

## 📂 Dataset Information (درباره دیتابیس)

The tool is pre-configured to fetch data from:

*   **Repository:** `yebekhe/bdata`
*   **Format:** Apache Parquet
*   **Columns:** `NATIONAL_CODE`, `FULL_NAME`, `MOBILE`, `FATHER_NAME`, `BANK_ACCOUNT`, `CITY`, `ADDRESS`.

> **Note:** If the Hugging Face repository is private or deleted, this search tool will stop working immediately.

---

## 🛠️ Usage (نحوه استفاده)

### Online Access
Simply visit the GitHub Pages link associated with this repository.

### Local Development
1.  Clone this repository.
2.  Open `index.html` in your browser.
3.  *Optional:* If you want to change the target dataset, edit these lines in the script:

```javascript
const HF_DATASET = "yebekhe/bdata"; // Change to your dataset
const HF_CONFIG = "default";
const HF_SPLIT = "train";
```

---

## ⚠️ Disclaimer (سلب مسئولیت)

**English:**
This project is for **Educational and Security Research purposes (OSINT)**.
1.  This repository contains **only HTML/JS code**. No PII (Personally Identifiable Information) is stored in this GitHub repository.
2.  The data acts as a public leak from Bank Mellat/Melli and is available on the public internet.
3.  The developer assumes no responsibility for the misuse of this tool.

**فارسی:**
این پروژه صرفاً جهت **پژوهش‌های امنیتی و OSINT** منتشر شده است.
1. این مخزن گیت‌هاب **هیچ‌گونه دیتایی** را میزبانی نمی‌کند و صرفاً یک رابط کاربری (Frontend) است.
2. دیتابیس متصل شده، مربوط به نشت اطلاعاتی عمومی بانک‌های ملت و ملی می‌باشد.
3.  مسئولیت قانونی نحوه استفاده از این ابزار تماماً بر عهده کاربر است.

---

## 📄 License

[MIT](LICENSE)
