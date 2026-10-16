# Awesome-Spreadsheet-Data-Tools

# Awesome-Spreadsheet-Data-Tools

## Top Spreadsheet Data Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on XLSX Read/Write, Formula Evaluation & Workbook Format Preservation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Spreadsheet Data Tools**. These tools help developers read, write, and manipulate Excel files programmatically — from generating reports and preserving complex workbook features to evaluating formulas and streaming large files.

**Examples** include SheetJS, Aspose.Cells, Syncfusion Excel Library, GrapeCity Documents for Excel, IronXL, EPPlus, Infragistics Excel Engine, DevExpress Office File API, GemBox.Spreadsheet, and SpreadsheetGear (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, format-preserving manipulation, and transparent formula evaluation — ideal for developers prioritizing data sovereignty, avoiding per-developer licensing fees, and maintaining control over their spreadsheet processing pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global spreadsheet software and developer-first spreadsheet data tools market is currently valued at approximately **$13.5 billion to $18.2 billion**, projected to grow at a **CAGR of 11.8%** toward **$32+ billion** by the early 2030s, propelled by automated financial workflows, AI data pipelines, and headless workbook compilation.

The industry exhibits **moderate overall fragmentation with a bifurcated dynamic**:
- **Front-End Productivity Suites (Concentrated Oligopoly)**: End-user GUI spreadsheets are heavily consolidated around mega-suite ecosystems like Microsoft 365 (Excel) and Google Workspace (Sheets).
- **Programmatic Data Tools & Headless Calculation Engines (Highly Fragmented)**: The developer API, format preservation, and headless formula evaluation layer is dynamic and moderately-to-highly fragmented rather than winner-take-all. Specialized developer libraries and cloud data spreadsheets thrive across language runtimes (.NET, Java, Python, TypeScript, Rust, Go) by solving specific high-stakes requirements such as high-fidelity XML roundtripping, non-commercial self-hosting, formula AST compilation, and multi-gigabyte streaming without memory exhaustion.

## SaaS/Hosted Platforms

The following commercial SaaS products, enterprise developer APIs, and cloud platforms provide programmatic Excel manipulation, formula engines, and collaborative spreadsheet data operations.

> *Sorted descending by company size (valuation / annual revenue).*

| Platform & Provider | Company Size (Valuation / Revenue) | Starting Tier Price | Free Tier Limit / Free Trial Plan | Core Capabilities & Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Airtable](https://airtable.com/)** <br> *(Formagrid Inc.)* | **~$11.7 Billion** valuation <br> *($1.36B raised)* | **$20.00 / seat / mo** <br> *(Team plan billed annually)* | **Free Forever plan**: Unlimited bases, 1,000 records per base, 1 GB attachments, 100 automation runs/mo | Relational spreadsheet-database hybrid with programmatic REST API, automation webhooks, and interface designer. |
| **[Smartsheet](https://www.smartsheet.com/)** <br> *(Smartsheet Inc. / Blackstone)* | **$8.4 Billion** valuation <br> *(Acquired by Blackstone/Vista)* | **$9.00 / user / mo** <br> *(Pro plan billed annually)* | **30-day fully functional trial**; converts to **Free plan forever** for 1 user with up to 2 sheets after trial | Enterprise collaborative work management and spreadsheet workflows with automation, Gantt timelines, and REST APIs. |
| **[Coda](https://coda.io/)** <br> *(Coda Project Inc.)* | **~$1.4 Billion** valuation <br> *($140M raised)* | **$10.00 / Doc Maker / mo** <br> *(Pro plan billed annually)* | **Free Forever plan**: Unlimited unshared docs, up to 50 tables/views and 1,000 rows per doc | All-in-one collaborative canvas combining spreadsheets, relational docs, automated buttons, and custom formula packs. |
| **[DevExpress Office File API](https://www.devexpress.com/)** <br> *(Developer Express Inc.)* | **~$120M – $150M** <br> annual revenue | **$999.99 / dev / yr** <br> *(Office File API Subscription)* | **30-day fully functional free trial** with complete technical support; no credit card required | Enterprise document processing library for .NET with Excel spreadsheet creation, complex formula calculations, and PDF generation. |
| **[MESCIUS Documents for Excel](https://developer.mescius.com/document-solutions/excel-api-net)** <br> *(MESCIUS inc. / GrapeCity)* | **~$100M+** <br> annual revenue | **$1,499.00 / dev / yr** <br> *(Developer License)* | **30-day unrestricted trial key**; unactivated mode limits workbooks to 5 sheets, 100 rows, and watermark | High-speed server-side spreadsheet API for .NET and Java with 450+ Excel functions, sparklines, conditional formatting, and pivot tables. |
| **[Infragistics Excel Engine](https://www.infragistics.com/)** <br> *(Infragistics, Inc.)* | **~$90M – $120M** <br> annual revenue | **$1,295.00 / dev / yr** <br> *(Infragistics Ultimate subscription)* | **30-day fully functional free trial** without feature restrictions, includes full technical support | High-performance spreadsheet manipulation within .NET, Windows Forms, WPF, and Blazor ecosystems with native charting and filtering. |
| **[Equals](https://equals.com/)** <br> *(Equals Technologies, Inc.)* | **~$80M** valuation <br> *($22M+ Series A)* | **$29.00 / user / mo** <br> *(Creator plan billed annually)* | **14-day fully featured free trial** with unlimited SQL queries; free unlimited viewers forever | Next-generation cloud spreadsheet with native SQL querying, automated data warehouse sync (Snowflake, BigQuery), and BI dashboards. |
| **[Syncfusion Excel Library](https://www.syncfusion.com/excel-framework/)** <br> *(Syncfusion, Inc.)* | **~$70M – $90M** <br> annual revenue | **$395.00 / dev / mo** <br> *(Billed annually at $4,740 / yr for 5 devs)* | **Free Forever (Community License)** for orgs <$1M revenue & ≤5 devs; or **30-day unrestricted free trial** | Comprehensive .NET, Java, and Flutter Excel library supporting 400+ formula functions, charts, encryption, and zero server royalties. |
| **[Aspose.Cells](https://products.aspose.com/cells/)** <br> *(Aspose Pty Ltd / Posirion)* | **~$50M – $70M** <br> annual revenue | **$1,199.00** one-time perpetual <br> *(Small Business, 1 dev)* or **$99.00 / mo** *(Cloud API)* | **Free Evaluation forever** (adds watermark, max 100 open workbooks) or **30-day unrestricted trial license** | Standalone spreadsheet engine for .NET, Java, Python, C++ with 400+ formula functions, full formatting, and high-fidelity PDF/image export. |
| **[Row Zero](https://rowzero.io/)** <br> *(Row Zero, Inc.)* | **~$35M** valuation <br> *($10.5M raised)* | **$25.00 / user / mo** <br> *(Pro plan billed annually)* | **Free Forever plan**: Up to 3 workbooks, 10M cells per workbook, and connected integrations | Blazing-fast cloud spreadsheet engineered for billion-row datasets connected directly to Snowflake, Databricks, Postgres, and S3. |
| **[IronXL](https://ironsoftware.com/)** <br> *(Iron Software LLC)* | **~$20M – $30M** <br> annual revenue | **$749.00** one-time perpetual <br> *(Lite license, 1 dev)* | **30-day deployment trial key**; evaluation mode without key limits read/write to first 25 rows with watermark | Intuitive .NET spreadsheet library without Office Interop dependencies; reads, writes, and edits XLSX, XLS, CSV, and TSV files. |
| **[SpreadsheetGear](https://www.spreadsheetgear.com/)** <br> *(SpreadsheetGear LLC)* | **~$15M – $25M** <br> annual revenue | **$1,199.00** perpetual <br> *(.NET Standard single dev)* | **Free evaluation forever** limited to 1,000 rows × 100 cols × 10 sheets × 3 workbooks; **30-day unrestricted trial key** | Ultra-fast royalty-free .NET spreadsheet calculation and reporting engine with rich Windows Forms, WPF, and ASP.NET controls. |
| **[SheetJS Pro](https://sheetjs.com/pro)** <br> *(SheetJS LLC)* | **~$10M – $20M** <br> annual revenue | **$799.00 / yr** <br> *(SheetJS Pro Developer subscription)* | **Free Forever (Community edition)** for basic read/write without styling; **30-day trial** for SheetJS Pro | Commercial edition of SheetJS adding full styling preservation, conditional formatting, password protection, and custom number formats. |
| **[GemBox.Spreadsheet](https://www.gemboxsoftware.com/)** <br> *(GemBox Software d.o.o.)* | **~$5M – $12M** <br> annual revenue | **$790.00** one-time perpetual <br> *(1 developer license)* | **Free mode forever** limited to 150 rows per sheet and 5 sheets per workbook; **30-day unrestricted trial key** on request | Fast, lightweight .NET spreadsheet component with support for XLSX, XLS, ODS, CSV, HTML, and high-fidelity PDF conversion. |
| **[EPPlus](https://www.epplussoftware.com/)** <br> *(EPPlus Software AB)* | **~$5M – $10M** <br> annual revenue | **$749.00 / dev / yr** <br> *(Commercial Small Business license)* | **Free Forever** under PolyForm Noncommercial license for personal/non-profit use; **30-day commercial trial** | Robust, high-performance .NET library for creating and styling complex XLSX workbooks with rich chart, formula, and pivot table support. |

## Open-Source GitHub Projects

- **[xlsx-populate](https://github.com/dtjohnson/xlsx-populate)**  
  **The format-preservation champion for read/modify/write workflows.** A 2026 independent test found that **xlsx-populate preserved all data validations, cross-sheet dropdown references, and drawings** when round-tripping a complex workbook — while ExcelJS duplicated validations and SheetJS lost them entirely. Its approach: **preserve the original XML structure** rather than parsing into an internal model and regenerating. **Trade-off**: fewer than 1,000 GitHub stars vs SheetJS's 35,000+, and smaller ecosystem. **Best for critical workbooks where data validation rules and drawings must survive programmatic edits**.

- **[ExcelJS](https://github.com/exceljs/exceljs)**  
  **The popular choice for generating new workbooks from scratch.** 13,000+ GitHub stars, widely used. **Can store formulas and supplied results but cannot process formulas to generate results**. **Critical limitation**: sorting bug causes **data validations to duplicate** when reading ranges (7 rules became 14 in testing). **Best for generating fresh XLSX reports with simple validations and no cross-sheet references**.

- **[SheetJS (xlsx)](https://github.com/SheetJS/sheetjs)**  
  **The most downloaded Excel library on npm** — 35,000+ GitHub stars, ~2M weekly downloads. **Community version silently drops data validations on write, strips most styling, and bloated file size by 375KB** in independent testing. **Best for reading data or converting between formats** — not for round-tripping complex workbooks.

- **[HyperFormula](https://github.com/handsontable/hyperformula)**  
  **The strongest headless formula engine for JavaScript.** UI-independent with **extensive built-in function coverage**, Node/server-side setup, and browser integration. **Licensed under GPLv3 or a proprietary license**. **Best for embedding formula calculation in web apps or Node processes**.

- **[IronCalc](https://github.com/ironcalc/IronCalc)**  
  **The strongest adjacent open-source spreadsheet engine on the Rust/WASM side.** MIT/Apache 2.0 licensed. WebAssembly in the browser, embeddable use cases, and headless calculations. Programming docs describe using the **same computational engine from Python, Rust, and JavaScript**. **Best for teams wanting a broader spreadsheet engine ecosystem with multi-language portability**.

- **[@bilig/headless](https://github.com/proompteng/bilig)**  
  **A TypeScript WorkPaper runtime for Node.js services and coding agents.** Exposes **workbook object operations** around mutation, **formula readback, persistence, restore checks, and deterministic evaluator verification**. **The wedge**: most automation failures happen after writing a formula — which cells changed? did formulas recalculate? did persisted JSON restore correctly? **`npm run agent:verify`** changes inputs, checks dependent formula readback, serializes, restores, and verifies formulas survived. **Best for backend services and AI agents that must prove spreadsheet calculations**.

- **[modern-xlsx](https://github.com/OfficeDev/modern-xlsx)**  
  **Dependency-free TypeScript spreadsheet I/O for XLSX, CSV, and ODS** with built-in formula evaluation and streaming I/O. Features **fluent style builder, tables, named ranges, data validations, comments, hyperlinks, frozen panes, auto filters, and page setup**. **Best for modern TypeScript projects wanting lightweight XLSX manipulation**.

- **[xlwings](https://github.com/xlwings/xlwings)**  
  **BSD-licensed Python library that makes it easy to call Python from Excel and vice versa**. **Scripting**: automate Excel from Python with syntax close to VBA. **Macros**: replace VBA with Python. **UDFs**: write user-defined functions in Python (Windows only). **Numpy arrays and Pandas DataFrames fully supported**. **xlwings PRO** adds server deployment, reporting, and reader functionality under PolyForm Noncommercial or commercial license. **Best for Python developers automating Excel workflows**.

- **[Hucre](https://github.com/hucre-io/hucre)**  
  **Dependency-free TypeScript spreadsheet I/O for XLSX, CSV, and ODS** with built-in formula evaluation and streaming I/O. **Best for TypeScript projects wanting comprehensive spreadsheet file handling**.

### Additional Strong Open-Source Options

- **Formula.js** — Implements many Excel formula functions as direct JavaScript calls. Not a workbook engine but useful for formula evaluation.
- **Formualizer** — Embeddable spreadsheet formula engine for apps, services, and automation pipelines across Rust, Python, and JavaScript/WASM.
- **excel_community** — Community fork of the Dart `excel` library for reading, creating, and editing XLSX files with charts, borders, and formulas. MIT licensed.
- **gridjs-spreadsheet** — Browser-based spreadsheet component with React, Vue, and Angular adapters.

**Frameworks for building custom systems**: Combine **xlsx-populate** for format-preserving read/modify/write of complex workbooks, **ExcelJS** or **SheetJS** for generating fresh reports or reading data, **HyperFormula** or **@bilig/headless** for formula calculation and verification, **IronCalc** for Rust/WASM portability, and **xlwings** for Python-Excel bidirectional automation — to build a complete spreadsheet processing stack tailored to your preservation requirements, runtime, and formula needs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Spreadsheet data tools differ significantly in format preservation, formula evaluation, and licensing model. **A 2026 independent test found that xlsx-populate preserved data validations, cross-sheet references, and drawings while ExcelJS duplicated validations and SheetJS lost them entirely**. **ExcelJS and SheetJS cannot calculate formulas** — they store formulas and supplied results only. **EPPlus version 5+ is commercial/Polyform Noncommercial** — earlier LGPL versions remain available. **SpreadsheetGear offers royalty-free perpetual licensing** with a free tier limited to 1,000 rows × 100 columns × 10 worksheets × 3 workbooks.
- Self-hosted open-source solutions require proper testing against your specific workbook features (validations, drawings, conditional formatting) before production deployment.

---

**Made for developers, data engineers, and anyone working with Excel files programmatically.**  
Let's make spreadsheet data tools more open, format-preserving, and developer-friendly.
