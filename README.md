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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Aspose.Cells](https://products.aspose.com/cells/)**  
  **The most feature-complete commercial spreadsheet API** for .NET, Java, Python, and other platforms. Native APIs to create, edit, convert, and render Excel files with full fidelity. **All-platform family pack from $1,199**. Supports XLSX, XLS, ODS, CSV, JSON, HTML, PDF, and image export. Built-in formula calculation engine with 400+ Excel functions. **Best for enterprise applications requiring maximum format compatibility and broad platform support**.

- **[Syncfusion Excel Library](https://www.syncfusion.com/excel-framework/)**  
  **Transparent, affordable licensing with no distribution fees, per-server licensing, or royalties**. **Team license (5 developers) at $4,740** includes all document libraries plus UI controls. Supports XLS and XLSX formats with **400+ built-in functions**, charts, pivot tables, conditional formatting, data validation, and encryption. **Best for teams wanting comprehensive Excel capabilities at predictable cost**.

- **[GrapeCity Documents for Excel](https://www.grapecity.com/)**  
  Enterprise Excel API for .NET and Java with full workbook manipulation, formula calculation, and PDF export. Supports complex scenarios including pivot tables, sparklines, and custom number formats.

- **[IronXL](https://ironsoftware.com/)**  
  .NET Excel library with simple API for reading, writing, and manipulating spreadsheets. Supports XLSX, XLS, CSV, and TSV. **Best for .NET developers wanting straightforward Excel operations without complex setup**.

- **[DevExpress Office File API](https://www.devexpress.com/)**  
  Enterprise document processing library for .NET with Excel spreadsheet creation, editing, and conversion. Deep integration with DevExpress UI controls.

- **[GemBox.Spreadsheet](https://www.gemboxsoftware.com/)**  
  .NET Excel library for reading, writing, and converting spreadsheet files. Supports XLSX, XLS, CSV, HTML, PDF, and image formats.

- **[SpreadsheetGear](https://www.spreadsheetgear.com/)**  
  **Royalty-free perpetual licensing for .NET, .NET Standard, and Windows**. **Bundle at $1,799** includes .NET Framework, .NET Engine, and Windows editions with one year of updates and support. **Free no-cost license limited to 1,000 rows × 100 columns × 10 worksheets × 3 workbooks**. **Best for .NET teams wanting perpetual licensing and Windows Forms/WPF integration**.

- **[Infragistics Excel Engine](https://www.infragistics.com/)**  
  Excel creation and manipulation within the Infragistics Ultimate UI toolkit for .NET. Best for teams already using Infragistics controls.

- **[EPPlus](https://www.epplussoftware.com/)**  
  **Version 5+ uses Polyform Noncommercial / Commercial dual licensing**. **Earlier versions remain LGPL**. Feature-rich .NET library for creating advanced Excel spreadsheets with pivot tables, charts, and data validation. **Best for .NET teams that qualify for noncommercial licensing or are willing to purchase commercial licenses**.

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
