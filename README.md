# 📄 Multi-Vendor LPO Stamper

> A browser-based automation tool that processes Local Purchase Order (LPO) PDFs from four major UAE retailers — matching order numbers against Excel sales data and stamping Sales Order numbers automatically. Built to save sales operations teams hours of repetitive manual work every day.

### 🚀 [**Try the Live Demo →**](https://gcramkrishna01-gethub.github.io/multi-vendor-lpo-stamper/)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![PDF.js](https://img.shields.io/badge/PDF.js-FF0000?style=flat&logo=mozilla&logoColor=white)
![pdf-lib](https://img.shields.io/badge/pdf--lib-000000?style=flat)
![SheetJS](https://img.shields.io/badge/SheetJS-217346?style=flat&logo=microsoft-excel&logoColor=white)

---

## 🎯 The Problem

UAE sales operations teams receive LPO (Local Purchase Order) PDFs daily from multiple retail vendors. Each PDF needs its Sales Order number manually stamped in the correct location before being forwarded to the warehouse. For busy distributors, this means hours of repetitive clicking, typing, and verifying — across several different PDF formats, one per vendor.

## ✨ The Solution

A single HTML tool that runs entirely in your browser. Drop in vendor PDFs and your Excel sheet, and the tool matches order numbers and stamps Sales Order numbers at the right spot for each vendor's unique layout — then hands back a batch ZIP of stamped PDFs ready to send.

**Result:** A task that took hours now takes seconds.

---

## 🏪 Supported Vendors

| Vendor | Match Key | Special Features |
|--------|-----------|------------------|
| **Carrefour** | PO Number | Auto layout detection |
| **LULU** | PO Number | Multi-page support |
| **Union Coop** | BOF Number | Double-validation (BOF + total value match) |
| **Delivery Hero** | Order Number | Structured extraction |

---

## 🚀 Features

- **Drag & drop uploads** for PDFs and Excel files
- **PDF thumbnail previews** — visually confirm the right files loaded before processing
- **Automatic vendor detection** based on PDF content
- **Excel matching** using SheetJS (supports .xlsx and .xls)
- **Precise stamp placement** with per-vendor coordinates
- **Double-validation for Union Coop** — matches both BOF number AND total value to prevent mistakes
- **Batch ZIP download** — export all stamped PDFs at once
- **Modal PDF inspection** — preview results before downloading
- **100% client-side** — no data is uploaded to any server, ever

---

## 🛠️ Tech Stack

- **[PDF.js](https://mozilla.github.io/pdf.js/)** — PDF rendering and text extraction
- **[pdf-lib](https://pdf-lib.js.org/)** — PDF modification and stamping
- **[SheetJS (xlsx)](https://sheetjs.com/)** — Excel file parsing
- **[JSZip](https://stuk.github.io/jszip/)** — Batch ZIP export
- **Pure HTML/CSS/JavaScript** — no build step, no dependencies to install

---

## 📖 How to Use

1. Open the [**Live Demo**](https://gcramkrishna01-gethub.github.io/multi-vendor-lpo-stamper/)
2. Upload your Excel sheet containing order numbers and Sales Order numbers
3. Drag in one or more LPO PDFs from any supported vendor
4. Review the thumbnail previews to confirm the right files loaded
5. Click **Process** — the tool matches and stamps each PDF
6. Download individually or grab the full batch as a ZIP

---

## 🔒 Privacy & Security

All processing happens **locally in your browser**. Your PDFs and Excel data never leave your device — no servers, no uploads, no tracking. This is especially important for retail operations data which can contain sensitive pricing and customer information.

---

## 💼 Commercial Use

Customized versions of this tool are available for UAE distributors and FMCG companies — including support for additional vendors, custom matching rules, and per-company deployments with monthly support.

**Interested?** Reach out via [LinkedIn](https://www.linkedin.com/in/ram-krishnaa-g-c-31136021b/).

---

## 👤 Author

**Ram Krishna G C**  
Sales & Operations Coordinator @ Arla Foods | Aspiring Data Analyst  
📍 Sharjah, UAE

[LinkedIn](https://www.linkedin.com/in/ram-krishnaa-g-c-31136021b/) · [GitHub](https://github.com/gcramkrishna01-gethub)

---

<p align="center">
  <i>Built to automate the boring stuff — so sales ops teams can focus on what matters.</i>
</p>
