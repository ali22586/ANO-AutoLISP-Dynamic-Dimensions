# ANO: Dynamic Associative Dimensions & Measurement Automation 📏

[![AutoCAD LISP](https://img.shields.io/badge/AutoCAD-AutoLISP-blue.svg)](https://www.autodesk.com/)
[![Version](https://img.shields.io/badge/Version-10.3-brightgreen.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**ANO** is a powerful AutoLISP utility designed to automate the tedious process of dimensioning, measuring, and extracting length data in AutoCAD. Built specifically for civil engineers, architects, and technical office teams, it eliminates manual quantity surveying errors and drastically reduces drafting time.

## ✨ Key Features

* **Smart Polyline Segmentation:** Automatically calculates and dimensions every individual segment of a polyline (including arcs and bulges).
* **Dynamic UI (DCL):** A clean dialog box to control precision, scale factors, units (e.g., m, cm), text height, and offset distances.
* **Associative Dimensions:** Generated dimensions update automatically if the underlying geometry changes.
* **Auto-Numbering:** Assigns sequential IDs to each measured segment for easy tracking in reports.
* **Visual Highlighting:** Optionally changes the color of processed objects to prevent duplicate measurements.
* **Comprehensive Reporting:**
    * **AutoCAD Table:** Generates an on-screen summary table detailing IDs, object types, layers, and lengths, including a layer-by-layer grand total.
    * **CSV Export:** Exports all measurement data directly to Excel for advanced quantity surveying (MTO) and cost estimation.

## 🚀 How It Works (Demo)

> **![Demo of ANO Lisp](1.gif)**

## 🛠️ Installation & Usage

1.  Download the `ANO-v10.3.LSP` file.
2.  Open AutoCAD and type `APPLOAD` in the command line.
3.  Select the downloaded file and click **Load**.
4.  Type **`ANO`** in the command line to launch the tool.
5.  Configure your desired settings in the dialog box, pick your objects, and watch the automation work!

## 📸 Screenshots

* **Settings Interface:**
    > **[Capture.PNG]**
## 💼 Custom Automation & Consulting

This tool is a sample of what can be achieved through workflow automation in civil engineering and construction management. 

If your technical office requires **custom plugins**, **specialized quantity surveying scripts**, or **data processing applications** (AutoLISP / Python) tailored to your specific project needs, feel free to reach out.

**Author:** Ali Akbari
* **Email:** [ali.22586@gmail.com]
* **LinkedIn:** [www.linkedin.com/in/ali-akbary-b34507415 ]
* **Telegram:** [@aliakbary88](https://t.me/aliakbary88)

---
*Created with precision for modern engineering teams.*
