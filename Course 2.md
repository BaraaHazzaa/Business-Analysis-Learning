# IBM Business Analysis Course: Excel Track  
*Comprehensive Notes for Revision*

## Table of Contents
- [Video 1: Introduction to Spreadsheets](#video-1-introduction-to-spreadsheets)
- [Video 2: Spreadsheet Basics, Navigation & Data Selection](#video-2-spreadsheet-basics-navigation--data-selection)
- [Essential Excel Keyboard Shortcuts](#essential-excel-keyboard-shortcuts)
- [Key Insights from Data Professionals](#key-insights-from-data-professionals)
- [Formula Fundamentals](#formula-fundamentals)
- [Statistical Functions and Categories](#statistical-functions-and-categories)
- [Cell References](#cell-references)
- [Formula Errors and Troubleshooting](#formula-errors-and-troubleshooting)
- [Video 3: Dealing with Inaccurate, Empty, and Duplicated Data](#video-3-dealing-with-inaccurate-empty-and-duplicated-data)
- [Video 4: Changing Text Case, Fixing Date Formats, and Trimming Whitespace](#video-4-changing-text-case-fixing-date-formats-and-trimming-whitespace)
- [Video 5: Using Flash Fill and Text to Columns for Data Cleaning](#video-5-using-flash-fill-and-text-to-columns-for-data-cleaning)
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

## Key Insights from Data Professionals

### ✅ Advantages of Spreadsheets
| Benefit | Description | Professional Context |
|---------|-------------|----------------------|
| **Visual Clarity** | Data is cleanly laid out in tabular format, enabling easy visual inspection of structure, formats, and values. | *"You can see all the data cleanly laid out... very clear to anyone looking at a spreadsheet exactly what the data is."* |
| **All-in-One Tool** | Combines data storage, calculation, analysis (pivot tables, charts), and reporting in a single interface. Exports seamlessly from ERPs/systems. | *"Excel is really that one-stop-shop where you can perform calculations, analyze financial ratios, and export reports."* (CPA perspective) |
| **Powerful Functions** | INDEX MATCH, SUMIF, filtering, and pivot tables simplify analysis of 0-20K rows. Transforms "unmanageable" data into actionable insights. | *"I can take twenty-thousand lines... massage it, sort it, filter it, put in a pivot table, and get what I need."* |
| **Universal Accessibility** | No specialized software required. Serves as a "common language" for business communication. | *"We don't need any fancy tools... it's the commonly utilized language to communicate."* |
| **Bite-Sized Analysis** | Breaks complex datasets into manageable chunks through sorting/filtering. Ideal for ad-hoc exploration. | *"It’s all about making it more manageable and breaking it down into bite-size chunks."* |

### ⚠️ Limitations of Spreadsheets
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

## Formula Fundamentals

### Formula Structure: Core Components
Every Excel formula follows a consistent syntax made of these elements:

| Component | Description | Example |
|----------|-------------|---------|
| **Equal Sign (`=`)** | Required at the start; tells Excel this is a formula, not text | `=` |
| **Function** | Built-in operation (e.g., `SUM`, `AVERAGE`) | `SUM` |
| **Reference** | Cell or range to include in calculation; enclosed in parentheses | `B5`, `E2:E13` |
| **Operators** | Symbols that define the type of calculation: | |
| &nbsp;&nbsp;• Arithmetic | `+` (add), `-` (subtract), `*` (multiply), `/` (divide) | `B5 * 20` |
| &nbsp;&nbsp;• Comparison | `=`, `>`, `<`, etc. | `A1 > B1` |
| &nbsp;&nbsp;• Text | `&` for concatenation | `"Total: " & A1` |
| **Constants** | Fixed values entered directly (do not change) | `5`, `10%`, `1/1/2026` |

> 💡 **Example**: `=SUM(B5*20)` multiplies the value in B5 by 20, then sums the result (useful for tax or markup calculations).

### Building Basic Formulas

#### Manual vs. Efficient Syntax
- **Inefficient**: `=SUM(E2,E3,E4)` → works but impractical for large ranges  
- **Efficient**: `=SUM(E2:E4)` → uses **colon notation** to include all cells from E2 through E4  
- **For full column**: `=SUM(E2:E13)`  

#### Best Practice: Use Mouse or Keyboard Selection
1. Type `=SUM(`
2. Select the desired range using:
   - **Mouse drag**, or  
   - **`Shift + arrow keys`**
3. Press `Enter` → Excel automatically inserts the closing parenthesis

> ⚠️ **Avoid**: Typing each cell reference individually—it’s error-prone and inflexible.

### Copying Formulas: AutoFill & Relative References

#### How to Use the Fill Handle
1. Create a formula in the first cell (e.g., `=SUM(B2:B13)` in B15)
2. Hover over the **bottom-right corner** of the cell until the cursor becomes a **thin black cross** (the **Fill Handle**)
3. **Drag** across or down to copy the formula to adjacent cells

#### Key Behavior: Relative Referencing
- Original: `=SUM(B2:B13)` in **B15**
- After dragging to **C15**: `=SUM(C2:C13)`
- Excel **automatically adjusts** cell references based on relative position

> 💡 **Real-World Application**:  
> - Subtotal (B15): `=SUM(B2:B13)`  
> - Tax (B16): `=B15*20%` → drag to C16 → becomes `=C15*20%`  
> - Total (B17): `=B15+B16` → drag across → auto-adjusts per column

### Time-Saving Excel Shortcuts

| Feature | How to Use | Shortcut |
|--------|------------|----------|
| **AutoSum** | 1. Select cell below/next to data<br>2. Go to **Home → Editing → AutoSum**<br>3. Press `Enter` | `Alt + =` |
| **Double-Click Fill Handle** | Instantly copy formula down an entire column (stops at last contiguous data row) | Double-click fill handle |
| **Edit Formula** | Click cell → edit in formula bar, press `F2`, or double-click cell | `F2` |

> ✅ **Pro Workflow for Monthly Totals**:  
> 1. In F2, type `=SUM(B2:E2)`  
> 2. **Double-click the fill handle** → formula auto-fills down to F13 (no dragging needed)

### Practical Example: Sales Report with Subtotals, Tax, and Totals

#### Step-by-Step Setup
1. **Add headers**:  
   - Row 14: `Subtotals`  
   - Row 15: `Tax (20%)`  
   - Row 16: `Total`
2. **Subtotals**:  
   - B14: `=SUM(B2:B13)` → drag fill handle to E14
3. **Tax**:  
   - B15: `=B14*20%` → drag to E15
4. **Totals**:  
   - B16: `=B14+B15` → drag to E16
5. **Monthly Totals (by row)**:  
   - F2: Use **AutoSum** (`Alt + =`) or `=SUM(B2:E2)` → **double-click fill handle** to copy down
6. **Format as Currency**:  
   - Select all values → **Home → Number → $ (Currency)**

> 💡 **Column Width Tip**: Double-click the right edge of a column header to auto-fit content.

### Critical Concepts to Remember

| Concept | Explanation |
|--------|-------------|
| **Relative References** | Formulas adjust cell addresses when copied (e.g., `B2` → `C2` when dragged right) |
| **Fill Handle ≠ Move Handle** | • **Small black cross** (bottom-right) = **Copy/Fill**<br>• **Thin cross with arrows** (cell edge) = **Move** (deletes original!) |
| **AutoSum Requirement** | Only works with **contiguous data**—fails if blank rows/columns interrupt the range |
| **Order of Operations** | Use parentheses to control calculation sequence: `=(A1+B1)*C1` ≠ `=A1+B1*C1` |

> ⚠️ **Common Mistake**: Accidentally dragging the **Move Handle** instead of the Fill Handle → permanently deletes source data. Always verify cursor shape!

### Quick Reference Cheat Sheet
```
=SUM(B2:B13)          // Sum vertical range
=B14*20%              // Calculate 20% tax
=SUM(B2:E2)           // Sum horizontal range
Alt + =               // AutoSum shortcut
Double-click fill handle // Auto-fill formula down column
Ctrl + 1              // Open Format Cells dialog
```

---

## Statistical Functions and Categories

### Common Statistical Functions
Excel provides built-in statistical functions accessible via **Home → Editing → AutoSum dropdown** or **Formulas → Function Library**.

| Function | Purpose | How to Use | Notes |
|---------|---------|------------|-------|
| **AVERAGE** | Calculates mean of values | `=AVERAGE(B2:B13)` | Ignores text/blank cells |
| **MIN** | Finds smallest value | `=MIN(B2:B13)` | Returns lowest numeric value |
| **MAX** | Finds largest value | `=MAX(B2:B13)` | Returns highest numeric value |
| **COUNT** | Counts numeric entries | `=COUNT(B2:B13)` | Excludes text, blanks, errors |
| **MEDIAN** | Finds middle value | `=MEDIAN(B2:B13)` | • Odd count: exact middle value<br>• Even count: average of two middle values |

#### Step-by-Step Workflow:
1. Add row headings: `Average`, `Minimum`, `Maximum`, `Count`, `Median`
2. In B20:  
   - Click **Home → AutoSum → Average**  
   - Adjust range from default to `B2:B13`  
   - Press `Enter`
3. **Copy across**: Use Fill Handle to drag formula from B20 to E20
4. Repeat for MIN (B21), MAX (B22), COUNT (B23)
5. For MEDIAN (B24):  
   - **AutoSum → More Functions → Statistical → MEDIAN**  
   - Set range to `B2:B13`  
   - Copy across to E24

> 💡 **Pro Tip**: Always verify and adjust the auto-selected range—Excel often guesses incorrectly!

### Function Categories & Key Examples
Access all functions via **Formulas tab → Function Library group**:

| Category | Key Functions | Use Cases |
|----------|---------------|-----------|
| **Recently Used** | Dynamic list | Quick access to your frequent functions |
| **Financial** | `ACCRINT`, `RATE`, `PMT` | Loan calculations, investment analysis |
| **Logical** | `IF`, `AND`, `OR` | Conditional logic, decision rules |
| **Text** | `CONCAT`, `FIND`, `SEARCH` | • `CONCAT`: Joins text (modern replacement for `CONCATENATE`)<br>• `FIND`/`SEARCH`: Locate substrings (`FIND` is case-sensitive) |
| **Date & Time** | `NETWORKDAYS`, `WEEKDAY`, `WEEKNUM` | Business day calculations, date formatting |
| **Lookup & Reference** | `VLOOKUP`, `HLOOKUP`, `SORTBY` | Data matching, dynamic sorting |
| **Math & Trig** | `SUMIF`, `SUMPRODUCT`, `POWER` | Conditional sums, matrix operations, exponents |
| **Statistical** | `AVERAGE`, `MEDIAN`, `STDEV` | Descriptive statistics (beyond basic AutoSum) |
| **More Functions** | Engineering, Information | Specialized technical calculations |

> ⚠️ **Note**: `CONCATENATE` still works for backward compatibility, but `CONCAT` is preferred in newer Excel versions.

### Finding Functions Efficiently

#### Method 1: Insert Function Dialog Box
1. Go to **Formulas → Insert Function** (or press `Shift + F3`)
2. Choose approach:
   - **Browse by category**: Select category → pick function
   - **Search**: Type function name → click **Go** → select from results
   - **All functions**: Alphabetical list of all 400+ functions

#### Method 2: Formula AutoComplete
- Start typing `=` followed by function name (e.g., `=vlo`)
- Excel shows matching functions with tooltips
- Press `Tab` to accept suggestion

#### Method 3: Function Arguments Helper
- After typing function name + `(`, Excel displays syntax guide
- Example: `VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])`
- Hover over arguments to see descriptions

### Critical Best Practices

| Practice | Why It Matters |
|----------|----------------|
| **Always validate ranges** | AutoSum often selects wrong ranges—manually verify `B2:B13` vs `B2:B20` |
| **Use structured references** | When possible, convert data to **Tables** (`Ctrl + T`) for self-documenting formulas like `=AVERAGE(Sales[Q1])` |
| **Prefer newer functions** | Use `CONCAT` instead of `CONCATENATE`, `XLOOKUP` instead of `VLOOKUP` (if available) |
| **Document complex formulas** | Add comments (`Shift + F2`) explaining non-obvious logic |
| **Test edge cases** | Verify how functions handle:<br>• Blank cells<br>• Text in numeric ranges<br>• #DIV/0! errors |

> 💡 **Real-World Insight**:  
> Data Analysts spend 80% of time cleaning data—statistical functions only work correctly on **clean, numeric data**. Always check for hidden text, spaces, or error values first!

### Quick Reference: Essential Analyst Functions

| Function | Syntax | Example |
|----------|--------|---------|
| **SUMIF** | `=SUMIF(range, criteria, [sum_range])` | `=SUMIF(A2:A10, ">100", B2:B10)` |
| **VLOOKUP** | `=VLOOKUP(lookup, table, col, [range_lookup])` | `=VLOOKUP("Toyota", A2:D100, 3, FALSE)` |
| **IF** | `=IF(logical_test, value_if_true, value_if_false)` | `=IF(B2>100, "High", "Low")` |
| **CONCAT** | `=CONCAT(text1, [text2], ...)` | `=CONCAT(A2, " ", B2)` |
| **NETWORKDAYS** | `=NETWORKDAYS(start_date, end_date, [holidays])` | `=NETWORKDAYS(TODAY(), TODAY()+30)` |

---

## Cell References

### Understanding Cell Reference Types

Excel formulas use three types of cell references that control how cell addresses behave when copied:

| Reference Type | Syntax | Behavior When Copied | Use Case |
|----------------|--------|----------------------|----------|
| **Relative** | `A1` | Both column and row adjust relative to new location | Most common; for consistent patterns (e.g., summing columns) |
| **Absolute** | `$A$1` | Column and row **never change** | Fixed values (e.g., tax rates, constants) |
| **Mixed** | `A$1` or `$A1` | **One part fixed**, one part relative:<br>• `A$1` = relative column, absolute row<br>• `$A1` = absolute column, relative row | Row/column headers, lookup tables |

### Practical Examples & Behavior

#### 1. Relative References (Default Behavior)
- **Original formula in E4**: `=A1 + A3`
- **Copied to E5**: `=A2 + A4`  
  *(Both references shift down 1 row)*
- **Copied to C7**: `=C4 + C6`  
  *(References shift left 2 columns AND down 3 rows)*

> 💡 **When to use**: Calculations that should adapt to new locations (e.g., monthly totals across columns).

#### 2. Absolute References (Locked Cells)
- **Original formula in E4**: `=$A$1 + $A$3`
- **Copied anywhere**: Always remains `=$A$1 + $A$3`

> 💡 **When to use**:  
> - Tax rates (`=$B$1`)  
> - Fixed conversion factors  
> - Constants referenced across multiple formulas

#### 3. Mixed References (Partial Locking)
- **Original formula in G4**: `=A$1 + $A3`
  - `A$1`: Column **A** adjusts, row **1** stays fixed
  - `$A3`: Column **A** stays fixed, row **3** adjusts
- **Copied to G5**: `=A$1 + $A4`  
  *(Only the relative row in `$A3` changed to `$A4`)*
- **Copied to H4**: `=B$1 + $A3`  
  *(Only the relative column in `A$1` changed to `B$1`)*

> 💡 **Real-World Use**:  
> - **Multiplication tables**: `=$A2*B$1`  
> - **VLOOKUP with fixed table**: `=VLOOKUP(A2,$D$2:$F$100,2,FALSE)`

### How to Create References Quickly

| Method | Action |
|--------|--------|
| **Manual Entry** | Type `$` before column/row (e.g., `$A$1`) |
| **F4 Key Toggle** | With cursor in formula bar on a reference:<br>• Press `F4` once: `$A$1` (absolute)<br>• Press again: `A$1` (mixed)<br>• Press again: `$A1` (mixed)<br>• Press again: `A1` (relative) |
| **Formula Bar Selection** | Highlight reference → press `F4` to cycle through options |

> ⚠️ **Critical Tip**: Always verify references after copying formulas—Excel won’t warn you if logic breaks!

---

## Formula Errors and Troubleshooting

### Common Formula Errors & Fixes

| Error | Cause | Solution |
|-------|-------|----------|
| **`#####`** | Column too narrow OR negative date/time | Widen column or fix date calculation |
| **`#NAME?`** | Unrecognized text (e.g., `X` instead of `*` for multiply) | Replace invalid operators; check function spelling |
| **`#VALUE!`** | Wrong data type (e.g., text in math operation) | Clean data; use `VALUE()` or `TEXT()` functions |
| **`#DIV/0!`** | Division by zero | Use `IFERROR(formula, "N/A")` or check denominator |
| **`#REF!`** | Invalid cell reference (e.g., deleted cells) | Restore deleted cells or update references |
| **`#N/A`** | Value not available (common in `VLOOKUP`) | Verify lookup value exists; use `IFNA()` |

### Error Diagnosis Workflow

1. **Identify the error**: Look for colored triangles (green = potential error)
2. **Click the warning icon**: Shows error description (e.g., "Invalid name error")
3. **Use diagnostic tools**:
   - **Show Calculation Steps**: Highlights exact error location
   - **Help on this Error**: Opens Microsoft support documentation
   - **Edit in Formula Bar**: Jumps cursor to error spot
4. **Apply fixes**:
   - Correct syntax (e.g., `*` not `X`)
   - Validate data types
   - Check cell references
5. **Prevent recurrence**:
   - Use `IFERROR()` for risky formulas:  
     ```
     =IFERROR(VLOOKUP(A2,B:C,2,0), "Not Found")
     ```
   - Enable **Error Checking Options** (`File → Options → Formulas`)

> 💡 **Pro Insight**:  
> The `#####` "error" is just a display issue—**never** indicates calculation problems. Always widen columns first before troubleshooting!

### Quick Reference Cheat Sheet

| Task | Formula Example |
|------|-----------------|
| **Fixed tax rate** | `=B2*$E$1` |
| **Dynamic multiplication table** | `=$A2*B$1` |
| **Safe division** | `=IF(D2=0, "N/A", C2/D2)` |
| **Error-proof VLOOKUP** | `=IFNA(VLOOKUP(G2,A:D,4,0), "Missing")` |
| **Toggle reference type** | Select reference in formula bar → Press `F4` |

---

## Video 3: Dealing with Inaccurate, Empty, and Duplicated Data

### Introduction to Data Cleaning
- **Common Issues in Data**: Spelling mistakes, extra whitespace, wrong case in text, empty rows, missing values, inaccurate or duplicated data.
- **Impacts of Errors**: Formulas not working, unsuccessful sorting/filtering, inadequate visualization and presentation of findings.
- **Importance**: Data cleaning improves quality and usability, especially after collecting or importing data (manual or automated processes).

### Spell Checking
- **Process**: Similar to Microsoft Word or other word processors.
- **Steps**:
  1. Select the data range or column to check (e.g., Column K: Product Line, Column T: Country, Column X: Deal Size).
  2. Go to **Review tab → Spelling**.
  3. Review suggestions: Click **Change** to accept, choose another suggestion, or **Ignore** if correct.
- **Examples**:
  - Misspelled country names (e.g., typos in Column T).
  - Misspellings like "small" or "medium" in Deal Size (Column X).
- **💡 Tip**: Check one column at a time for targeted corrections.

### Removing Empty Rows
- **Issues Caused**: Problems with navigation (e.g., `Ctrl + ↓` stops at empty rows), formulas, sorting, and filtering. Splits dataset into sections.
- **Manual Method**: Scroll and delete rows individually—suitable for small datasets but laborious for large ones (hundreds/thousands of rows).
- **Efficient Method Using Filters**:
  1. Select all data (mouse or `Ctrl + Shift + End`).
  2. Go to **Data tab → Filter**.
  3. Click filter icon on a column (e.g., Customer Name in Column M).
  4. Uncheck **Select All**, scroll to bottom, check **Blanks**, click **OK**.
  5. Empty rows appear at top (identified by row numbers in blue, e.g., rows 28, 29, 65, 73-75, 117).
  6. Select these rows (mouse or from first blank cell like A28, then `Ctrl + Shift + End`).
  7. Delete the rows.
  8. Clear filter: **Data tab → Clear** (or turn off Filter).
- **Verification**: Use `Ctrl + ↓` from top to ensure it jumps directly to the end of the data.
- **⚠️ Warning**: Empty rows can make datasets appear fragmented.

### Removing Duplicated Rows
- **Causes**: Human input errors or import process issues.
- **Key Principle**: Select a column unlikely to have natural duplicates (e.g., Sales in Column E, not Price Each in Column C).
- **Method 1: Review Before Deleting (Preferred for Security)**:
  1. Select the column (e.g., Sales in E).
  2. Go to **Home tab → Conditional Formatting → Highlight Cells Rules → Duplicate Values**.
  3. Click **OK**—duplicates are highlighted (e.g., rows 36-40 and 74-78).
  4. Review: Zoom out to compare sections (e.g., out-of-sequence duplicates like Motorcycles in Ships section).
  5. Delete the duplicate rows manually (e.g., second section).
- **Method 2: Quick Removal (Simpler but Less Secure)**:
  1. Select entire dataset.
  2. Go to **Data tab → Remove Duplicates**.
  3. Unselect all columns, then select only the key column (e.g., Sales).
  4. Click **OK**—duplicates are removed automatically.
- **💡 Tip**: Always preview duplicates in Method 1 to avoid accidental data loss.

### Using Find & Replace for Corrections
- **Location**: **Home tab → Find & Select → Replace**.
- **Steps**:
  1. Enter incorrect text in **Find what** (e.g., misspelled surname "Larson").
  2. Click **Find Next** or **Find All** to list instances.
  3. Enter correction in **Replace with** (e.g., "Larsson").
  4. Click **Replace All**.
- **Example**: Correcting multiple instances of a misspelled customer surname based on email feedback.
- **✅ Pro Tip**: Familiar from other Office apps like Word; use for batch corrections like names or terms.

### Key Takeaways
- Focus on spell checking, empty rows, duplicates, and find/replace to handle common inaccuracies.
- Improves data quality post-import/collection.
- Next: Changing text case, fixing date formats, trimming whitespace.

---

## Video 4: Changing Text Case, Fixing Date Formats, and Trimming Whitespace

### Introduction
- **Common Issues**: Mixed case text (uppercase, lowercase, proper case) from varying sources; inconsistent or region-unsuitable date formats; unwanted whitespace (leading/trailing spaces, double spaces).
- **Importance**: Standardize text for consistency; ensure dates are readable and compatible; remove whitespace to prevent errors in formulas, sorting, and analysis.
- **Tools**: Functions like UPPER, LOWER, PROPER for case; Number Format dialog for dates; Find & Replace and TRIM for whitespace.

### Changing Text Case Using Functions
- **No Direct Button**: Unlike Word, use UPPER, LOWER, PROPER functions with helper rows/columns.
- **PROPER Function (Proper Case)**:
  - **Example**: Change header row (e.g., Row 1) from uppercase to proper case.
  - **Steps**:
    1. Insert helper row (e.g., Row 2).
    2. In A2: `=PROPER(A1)`, press Enter.
    3. Fill across: Select A2:X2 (Shift + Right Arrow), press F2 to edit A2, then Ctrl + Enter.
    4. Copy Row 2, paste to Row 1 using **Paste Values** (Home tab → Paste → Paste Values).
    5. Delete helper row (avoid direct delete to prevent #REF! errors).
- **UPPER Function (Uppercase)**:
  - **Example**: Change proper case to uppercase (e.g., Country in Column T).
  - **Steps**:
    1. Insert helper column (e.g., to right of T).
    2. In new cell (e.g., U2): `=UPPER(T2)`, press Enter.
    3. Double-click Fill Handle to copy down.
    4. Copy helper column, paste to original (T) using **Paste Values**.
    5. Delete helper column.
- **LOWER Function (Lowercase)**:
  - **Example**: Change proper case to lowercase (e.g., Product Line in Column K).
  - **Steps**: Same as UPPER, but use `=LOWER(K2)`.
- **⚠️ Warning**: Always use Paste Values to avoid formula references breaking.
- **💡 Tip**: Double-click Fill Handle for quick vertical copy; use for large datasets.

### Fixing Date Formatting Errors
- **Common Issues**: Mixed formats (e.g., DD/MM/YYYY vs. MM/DD/YYYY); region mismatches.
- **Steps for Standard Formats**:
  1. Select date column.
  2. Open **Format Cells** (Ctrl + 1) → Number tab → Date category.
  3. Change Locale (e.g., from English (UK) to English (US)).
  4. Select a format (e.g., full month name, 2-digit day, 4-digit year).
  5. Apply and copy format down if needed.
- **Custom Formats**:
  1. In Format Cells → Custom category.
  2. Modify an existing format (e.g., change to "dd mmm yyyy" for day, 3-letter month, year).
  3. Apply to selection or use Format Painter (Home tab) to copy to rest of column.
- **✅ Pro Tip**: Select entire column for batch formatting; custom formats persist in the list for reuse.

### Trimming Whitespace
- **Types**: Leading/trailing spaces, double spaces between words.
- **Using Find & Replace (for Double Spaces)**:
  1. Select data range.
  2. Home tab → Find & Select → Replace.
  3. **Find what**: Double space (press space twice).
  4. **Replace with**: Single space.
  5. Click **Find Next** and **Replace** individually (safer), or **Replace All** for large datasets.
- **Limitations**: Can't remove single leading/trailing spaces without affecting word spaces.
- **TRIM Function (for All Extra Spaces)**:
  - **Steps**:
    1. Insert helper column (e.g., next to Column M: Customer Name).
    2. In helper cell (e.g., N2): `=TRIM(M2)`, press Enter.
    3. Double-click Fill Handle to copy down.
    4. Copy helper column, paste to original (M) using **Paste Values**.
    5. Delete helper column.
- **💡 Tip**: TRIM removes leading/trailing and reduces multiple internal spaces to single; combine with Find & Replace for thorough cleaning.
- **⚠️ Warning**: Replace All can save time but verify changes to avoid unintended removals.

### Key Takeaways
- Use helper rows/columns with case functions and Paste Values for text standardization.
- Format Cells dialog for date adjustments, including custom formats.
- Find & Replace for double spaces; TRIM for comprehensive whitespace removal.
- Next: Using Flash Fill and Text to Columns for data cleaning.

---

## Video 5: Using Flash Fill and Text to Columns for Data Cleaning

### Introduction
- **Flash Fill Recap**: Previously used for patterned data entry (e.g., months, days); also useful for cleaning by splitting/combining names or modifying naming conventions.
- **Text to Columns**: Splits multi-part text (e.g., full names, addresses) into separate columns; not available in Excel for the web—use functions instead.
- **Functions Alternative**: More flexible for complex/mixed names (e.g., hyphenated, middle initials).
- **Context**: Applied to datasets like vehicle toy sales (separate first/last names) or customer contacts (full names).

### Using Flash Fill to Combine Columns
- **Purpose**: Combine separate name columns (e.g., first and last) into one formatted column.
- **Steps** (e.g., Combining First and Last Names):
  1. Insert a helper column (e.g., "Contactname").
  2. In the first data row: Enter the desired format (e.g., Forename space Surname from original columns).
  3. Press Enter.
  4. Start typing the second entry—Flash Fill previews the pattern.
  5. Press Enter to apply to the entire column.
- **Examples**:
  - Handles variations like "Wing C" or "Da Cunha".
- **Cleanup**: Remove original columns if no longer needed.
- **💡 Tip**: Flash Fill detects patterns automatically; works for custom formats (e.g., Surname, Comma, Forename).

### Using Flash Fill to Modify Naming Conventions
- **Purpose**: Change format in a single column (e.g., from Forename Surname to Surname, Comma, Forename).
- **Steps** (e.g., Customer Contacts Worksheet):
  1. In adjacent column's first data row (e.g., B2): Enter new format (e.g., Surname, comma, space, Forename).
  2. Press Enter.
  3. Start typing second entry—Flash Fill previews.
  4. Press Enter to fill down.
  5. Copy/paste header if needed; delete original column.
- **Limitations**: Can't split a single column into multiple—use Text to Columns for that.
- **⚠️ Warning**: Close without saving if testing; Flash Fill is pattern-based, so verify previews.

### Using Text to Columns to Split Data
- **Purpose**: Split multi-part text into separate columns (e.g., full names into first/last).
- **Steps** (e.g., Customer Contacts Worksheet):
  1. Add/widen headers for new columns (e.g., First Name, Last Name).
  2. Select data range (e.g., A2:A23).
  3. Go to **Data tab → Text to Columns** (launches wizard).
  4. Step 1: Select **Delimited**.
  5. Step 2: Check **Space** as delimiter (uncheck others).
  6. Step 3: Set Destination (e.g., B2) via arrow selector.
  7. Click **Finish**.
- **Result**: Splits names into new columns (e.g., B and C).
- **Cleanup**: Remove original column if unnecessary.
- **✅ Pro Tip**: Use for any delimited text like addresses; preview in wizard.

### Using Functions as an Alternative to Text to Columns
- **When to Use**: In Excel for the web (no Text to Columns); for complex names (hyphenated, middle initials).
- **Steps** (e.g., Splitting Full Names):
  1. Add/widen headers for new columns (e.g., Forename, Surname).
  2. For Forename (e.g., B2): `=LEFT(A2,5)` (extracts left characters, adjust count as needed; includes space if present).
  3. For Surname (e.g., C2): `=RIGHT(A2,7)` (extracts right characters, adjust count).
  4. Double-click Fill Handle on B2 and C2 to AutoFill down.
- **Flexibility**: Customize for variations (e.g., handle middle initials by adjusting lengths or using more advanced functions like MID).
- **💡 Tip**: Test formulas on sample data; combine with LEN or FIND for dynamic extraction.

### Key Takeaways
- Flash Fill: Quick for combining/modifying based on patterns; preview before applying.
- Text to Columns: Ideal for splitting delimited text; wizard-guided.
- Functions: Versatile alternative for web Excel or complex cases.
- Always use helpers/previews to avoid data loss.
- Next: Further data cleaning topics (not specified in transcript).

---