# TECO Excel Cleaner (v7.00 Stable)

This PowerShell script provides a graphical user interface (GUI) for automatically cleaning and extracting the first work note entry from large ServiceNow export files (`incident*.xlsx` or `sc_task*.xlsx`).

This version (`v7.00`) is the official **High-Speed Stable** release, utilizing a streamlined single-threaded architecture optimized for peak performance.

## 🚀 Getting Started

### 1. Prerequisites
You must have the PowerShell `ImportExcel` module installed. Run the following command in PowerShell if prompted:
```powershell
Install-Module -Name ImportExcel -Scope CurrentUser
```

### 2. How to Run
1. Clone or add this repository to **GitHub Desktop**.
2. Open `TecoExcelCleaner.ps1` or run it directly with PowerShell.

### 3. Features
* **Easy (Auto):** Automatically scans your `Downloads` folder for today's incident and task Excel exports and cleans them.
* **Select File:** Manually browse for any ServiceNow export file.
* **Audit Logs:** Automatically logs operations and cleans up logs older than 30 days.
