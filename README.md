# Excel Comparison Tool

A desktop application for comparing two Excel files and generating a highlighted comparison report.

## Overview

The application provides a simple workflow to select two Excel files, compare their data at the cell level, and generate a highlighted Excel report showing the comparison results.

## Application Workflow

```text
1. Launch Application
        |
        v
2. License Key Authentication
        |
        v
3. Select Excel Files
   ├── Original Excel (Base File)
   └── Modified Excel (Modified File)
        |
        v
4. Run Smart Comparison Engine
        |
        v
5. Generate Comparison Report
```

## Workflow Details

### 1. Launch Application

Start the application to access the Excel comparison functionality.

### 2. License Key Authentication

Enter and validate the license key before proceeding with the comparison.

### 3. Select Excel Files

Select two Excel files for comparison:

- **Original Excel (Base File)**
- **Modified Excel (Modified File)**

### 4. Run Smart Comparison Engine

The comparison engine analyzes and compares the Original and Modified Excel files at the cell level.

### 5. Generate Comparison Report

A highlighted Excel report is generated to make the comparison results easy to identify.

## Comparison Results

The generated report uses color highlighting to identify different cell states.

| Color | Result | Description |
|---|---|---|
| 🟩 Green | **Unchanged Cell** | Values are the same in both files |
| 🟥 Red | **Modified Cell** | Values are different between the files |
| 🟨 Yellow | **Added Cell** | Cell is present in the Modified file but not in the Original |
| ⬜ Gray | **Deleted Cell** | Cell is present in the Original file but missing in the Modified file |

## Example Result

The generated report visually highlights cells according to their comparison result:

```text
Original Excel          Modified Excel
     |                       |
     +----------+------------+
                |
                v
       Comparison Process
                |
                v
       Highlighted Report
```

### Result Legend

```text
GREEN  → Unchanged
RED    → Modified
YELLOW → Added
GRAY   → Deleted
```

## Key Features

- Launch application with license key authentication
- Select two Excel files for comparison
- Compare Excel data at cell level
- Generate a highlighted Excel report
- Clearly distinguish unchanged, modified, added, and deleted cells
- Keep comparison results easy to review visually

## Requirements

- Java 17 or later
- Maven
- Microsoft Excel or a compatible spreadsheet application for viewing the generated report

## 📩 Want to Try It?

If you would like to try the application, test the Excel comparison workflow, or share feedback, feel free to get in touch.

**Email:** rajat1ruikar@gmail.com

Feedback, suggestions, and testing experiences are welcome.

## Project Status

🚧 **Fully Development, Under Testing**

Current functionality is focused on the Excel comparison workflow and highlighted comparison reporting.
