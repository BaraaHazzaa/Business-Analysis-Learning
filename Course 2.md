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
```excel
=SUM(B2:B13)          // Sum vertical range
=B14*20%              // Calculate 20% tax
=SUM(B2:E2)           // Sum horizontal range
Alt + =               // AutoSum shortcut
Double-click fill handle // Auto-fill formula down column
Ctrl + 1              // Open Format Cells dialog

---

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

---

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

---

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

---

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

---

### Quick Reference: Essential Analyst Functions

| Function | Syntax | Example |
|----------|--------|---------|
| **SUMIF** | `=SUMIF(range, criteria, [sum_range])` | `=SUMIF(A2:A10, ">100", B2:B10)` |
| **VLOOKUP** | `=VLOOKUP(lookup, table, col, [range_lookup])` | `=VLOOKUP("Toyota", A2:D100, 3, FALSE)` |
| **IF** | `=IF(logical_test, value_if_true, value_if_false)` | `=IF(B2>100, "High", "Low")` |
| **CONCAT** | `=CONCAT(text1, [text2], ...)` | `=CONCAT(A2, " ", B2)` |
| **NETWORKDAYS** | `=NETWORKDAYS(start_date, end_date, [holidays])` | `=NETWORKDAYS(TODAY(), TODAY()+30)` |

---