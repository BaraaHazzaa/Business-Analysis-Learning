# IBM Business Analysis Course: Excel Track  
*Comprehensive Notes for Revision*

---

## Video 1: Introduction to Spreadsheets

### Common Spreadsheet Applications
| Application          | Type             | Cost                          | Key Features/Notes                                                                 |
|----------------------|------------------|-------------------------------|----------------------------------------------------------------------------------|
| **Microsoft Excel**  | Desktop & Web    | Paid (desktop); Free web version | Most feature-rich; part of Microsoft Office/365                                |
| **Google Sheets**    | Web-based        | Free (with Google account)    | Integrates with Google Forms, Analytics, Data Studio                           |
| **LibreOffice Calc** | Desktop          | Free & open-source            | Basic but sufficient for analysis (pivot tables, charts, conditional formatting) |
| **Zoho Sheet**       | Web-based        | Free tier available           | Comparable to Google Sheets                                                     |
| **OpenOffice Calc**  | Desktop          | Free & open-source            | Older alternative to LibreOffice                                                |
| **Quip (Salesforce)**| Web/Desktop      | Part of Salesforce ecosystem  | Collaboration-focused                                                           |
| **Smartsheet**       | Web-based        | Paid (freemium)               | Geared toward project management                                                |
| **Apple Numbers**    | Desktop/Mobile   | Free (for Apple users)        | Optimized for macOS/iOS                                                         |

> **💡 Takeaway**: Choose based on features, budget, platform, and integration needs.

### Key Capabilities of Spreadsheets
- **Automated Calculations**: Formulas ensure accuracy and save time.
- **Data Organization**: Easy to structure, format, sort, and filter.
- **Error Handling**: Mistakes can be edited, undone, or flagged via built-in tools.
- **Data Visualization**: Create charts, graphs, and reports to communicate insights.
- **Scalability**: Evolved from simple tables (1970s VisiCalc) to powerful analysis platforms.

### Common Business Uses
- Data entry & storage  
- Comparing large datasets  
- Financial modeling & forecasting  
- Budgeting & profit/loss accounting  
- Payroll, tax reporting, invoicing  
- Sales tracking & trend identification  
- Statistical analysis  
- Business process flowcharts  
- Scheduling

### Personal & Non-Business Uses
- Household budgeting  
- Fitness tracking & calorie counting  
- Recipe/music libraries  
- Sports leagues (e.g., Fantasy Football)  
- Contact/shopping lists

### Why Spreadsheets Matter for Data Analysts
1. **Data Collection**: Gather from multiple distributed sources.  
2. **Data Cleaning**: Remove duplicates, fix errors, handle missing values.  
3. **Data Analysis**: Filter, sort, and interpret to extract insights.  
4. **Data Visualization**: Communicate findings to stakeholders.

---

## Video 2: Spreadsheet Basics, Navigation & Data Selection

### Core Terminology
| Term          | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| **Workbook**  | Main Excel file (`.xlsx`). Contains worksheets, data, calculations.       |
| **Worksheet** | Single tab within workbook (e.g., `Sheet1`).<br>– Rename: Double-click tab or right-click → **Rename**.<br>– Reorder: Drag tabs or right-click → **Move or Copy**. |
| **Cell**      | Individual box holding data. Identified by **column letter + row number** (e.g., `M20`). |
| **Active Cell** | Currently selected cell (highlighted border + shown in Name Box top-left). |
| **Cell Range** | Group of cells (e.g., `D9:D19`).<br>– Notation: `StartCell:EndCell`<br>– Used in formulas and 3D references (across worksheets). |

> **💡 Tip**: Always reference column first, then row (e.g., `B7`, not `7B`).

### Excel Interface Navigation
#### Ribbon & Menus
- **Tabs**: Home, Insert, Formulas, Data, etc.  
- **Groups**: Organized commands (e.g., Font, Alignment on Home tab).  
- **Expand groups**: Click ↘ icon in bottom-right corner of group.  
- **Hide/Show Ribbon**:  
  – Double-click any tab  
  – Or press `Ctrl + F1`

#### Quick Access Toolbar (QAT)
- Top-left, above ribbon.  
- Default tools: Save, Undo, Redo, New, Open.  
- **Customize**: Add tools via dropdown arrow (e.g., Sort Ascending/Descending).

#### Backstage View (`File` tab)
- Create new workbooks, open files (`Open` → `Browse`), save, print, access Excel Options.

### Navigation Shortcuts
| Action                          | Shortcut             |
|---------------------------------|----------------------|
| Move 1 cell                     | Arrow keys           |
| Jump to start (A1)              | `Ctrl + Home`        |
| Jump to last used cell          | `Ctrl + End`         |
| Go to end of current column     | `Ctrl + ↓`           |
| Return to top of column         | `Ctrl + ↑`           |
| Move one screen down/up         | `Page Down`/`Page Up`|
| Move to next/previous worksheet | `Ctrl + Page Down`/`Ctrl + Page Up` |

> **✅ Pro Tip**: Use `Ctrl + ↓` from first data cell to find total rows (e.g., 160 rows).

### Data Selection Methods
| Selection Type              | How To                                                                 |
|-----------------------------|------------------------------------------------------------------------|
| **Single cell**             | Click or arrow keys                                                    |
| **Contiguous range**        | Drag mouse **or** `Shift + arrow keys`                                |
| **Entire column/row**       | Click column letter (e.g., **B**) or row number (e.g., **7**)        |
| **Non-contiguous ranges**   | Select first range → hold `Ctrl` → click other columns/rows           |
| **Entire worksheet**        | Click ▢ at top-left corner (above row 1, left of column A)            |
| **Data only (not empty)**   | Press `Ctrl + A` once                                                  |

### Mouse Pointer Symbols
| Cursor       | Appearance                     | Function                     |
|--------------|--------------------------------|------------------------------|
| **Select**   | Large white cross              | Standard cell selection      |
| **Move**     | Thin black cross with 4 arrows | Drag to **move** cell contents |
| **Fill Handle** | Small black cross (bottom-right) | Drag to **copy/fill** data   |

> **⚠️ Warning**: Accidental drag with Move/Fill handles can alter data!

---

## Essential Excel Keyboard Shortcuts

### 📁 File & Workbook Management
| Task             | Shortcut    |
|------------------|-------------|
| Open workbook    | `Ctrl + O`  |
| Save workbook    | `Ctrl + S`  |
| Close workbook   | `Ctrl + W`  |

### ✂️ Editing & Clipboard
| Task               | Shortcut       |
|--------------------|----------------|
| Copy               | `Ctrl + C`     |
| Cut                | `Ctrl + X`     |
| Paste              | `Ctrl + V`     |
| Undo               | `Ctrl + Z`     |
| Remove contents    | `Delete`       |
| Edit active cell   | `F2`           |

### 🔤 Formatting
| Task       | Shortcut    |
|------------|-------------|
| Bold text  | `Ctrl + B`  |

### 🖱️ Navigation & Selection
| Task                                      | Shortcut               |
|-------------------------------------------|------------------------|
| Move to edge of data region               | `Ctrl + Arrow key`     |
| Go to beginning of worksheet (A1)         | `Ctrl + Home`          |
| Go to last used cell                      | `Ctrl + End`           |
| Extend selection to last used cell        | `Ctrl + Shift + End`   |
| Move one screen left/right                | `Alt + Page Up/Down`   |

### 📅 Date & Time Entry
| Task               | Shortcut          |
|--------------------|-------------------|
| Insert current date| `Ctrl + ;`        |
| Insert current time| `Ctrl + Shift + :`|

### ⚙️ Interface & Menus
| Task                     | Shortcut       |
|--------------------------|----------------|
| Expand/collapse ribbon   | `Ctrl + F1`    |
| Open context menu        | `Shift + F10`  |

---

### 💡 Key Insights from Data Professionals

#### ✅ **Advantages of Spreadsheets**
| Benefit | Description | Professional Context |
|---------|-------------|----------------------|
| **Visual Clarity** | Data is cleanly laid out in tabular format, enabling easy visual inspection of structure, formats, and values. | *"You can see all the data cleanly laid out... very clear to anyone looking at a spreadsheet exactly what the data is."* |
| **All-in-One Tool** | Combines data storage, calculation, analysis (pivot tables, charts), and reporting in a single interface. Exports seamlessly from ERPs/systems. | *"Excel is really that one-stop-shop where you can perform calculations, analyze financial ratios, and export reports."* (CPA perspective) |
| **Powerful Functions** | INDEX MATCH, SUMIF, filtering, and pivot tables simplify analysis of 0-20K rows. Transforms "unmanageable" data into actionable insights. | *"I can take twenty-thousand lines... massage it, sort it, filter it, put in a pivot table, and get what I need."* |
| **Universal Accessibility** | No specialized software required. Serves as a "common language" for business communication. | *"We don't need any fancy tools... it's the commonly utilized language to communicate."* |
| **Bite-Sized Analysis** | Breaks complex datasets into manageable chunks through sorting/filtering. Ideal for ad-hoc exploration. | *"It’s all about making it more manageable and breaking it down into bite-size chunks."* |

#### ⚠️ **Limitations of Spreadsheets**
| Limitation | Description | Real-World Impact |
|------------|-------------|-------------------|
| **Poor Reproducibility** | No audit trail for data transformations (e.g., filtering bad values, imputing missing data). Steps can't be easily shared or repeated. | *"There's no way to tell your colleagues or future self exactly the steps you took to modify that dataset."* |
| **Analysis Paralysis** | Overwhelming function options lead to wasted time troubleshooting complex formulas instead of solving problems. | *"You may spend a lot more time... trying to figure out one Excel function when a manual approach would be faster."* |
| **Formula Fragility** | Complex formulas (VLOOKUP, nested IFs) break unexpectedly, requiring rebuilding. | *"If you have complex formulas... they just stop working and you have to rebuild them."* |
| **Scalability Limits** | Performance degrades >20K rows; frequent crashes with large datasets. | *"If I start to get over ten, twenty-thousand lines... spreadsheets will crash."* |
| **Limited Advanced Analysis** | Inadequate for complex statistical modeling, big data, or sophisticated visualizations. | *"Spreadsheets have less flexibility for complicated analysis and presentation."* |

### 🔑 Critical Takeaways
1. **Right Tool for the Job**:  
   - ✅ **Use spreadsheets for**:  
     - Small-to-medium datasets (<20K rows)  
     - Quick ad-hoc analysis and reporting  
     - Situations requiring universal accessibility  
   - ❌ **Avoid spreadsheets for**:  
     - Large-scale/complex analyses  
     - Reproducible data pipelines  
     - Mission-critical calculations requiring audit trails  

2. **Professional Workflow Tip**:  
   > *"I love Excel for simple analysis and data downloads... but when datasets grow, we move to Access or other tools."*  
   – **Hybrid Approach**: Use spreadsheets for initial exploration → transition to databases (SQL), Python/R, or BI tools (Power BI, Tableau) for heavy lifting.

3. **Mitigating Limitations**:  
   - Document manual steps in a "Notes" tab when cleaning data  
   - Avoid overly complex nested formulas; break logic into helper columns  
   - Use Power Query (Get & Transform) for reproducible data transformations  

---