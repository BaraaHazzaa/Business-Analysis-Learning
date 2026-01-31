# IBM Business Analysis Course: Course 3 - Data Visualization
*Comprehensive Notes for Revision*

## Table of Contents
- [Video 1: Overview of Charts and Visualizations](#video-1-overview-of-charts-and-visualizations)
- [Summary of Chart Types](#summary-of-chart-types)

---

## Video 1: Overview of Charts and Visualizations

### Introduction to Data Storytelling
Data visualization is the practice of shaping raw data into graphical representations to provide meaningful information. The goal is to choose a chart that best tells the "story" of the data, whether that is showing a trend, a proportion, or a complex hierarchy.

### Summary of Chart Types

| Chart Type | Best Used For | Key Characteristics |
| :--- | :--- | :--- |
| **Line Chart** | Trends over time | Displays changes in relation to a continuous variable. |
| **Pie Chart** | Parts of a whole | Represents static categories that must sum to 100%. |
| **Bar Chart** | Comparison | Great for comparing related datasets; very easy to read. |
| **Column Chart** | Time & Comparisons | Vertical orientation; ideal for showing positive vs. negative values. |
| **Treemap** | Hierarchies | Uses nested rectangles; size and color represent different data points. |
| **Funnel Chart** | Process Pipelines | Visualizes stages of a continuous process (e.g., sales stages). |
| **Scatter Chart** | Relationships | Reveals correlations, clusters, and patterns using circle size/color. |
| **Bubble Chart** | Significance | A variant of scatter charts for comparing a few categories by volume. |
| **Sparklines** | Micro-trends | Small charts without axes; shows general variations at a glance. |

---

### Detailed Insights

#### 📈 Line and Trend Analysis
* **Line Charts:** Specifically designed for **continuous variables**. 
    * *Example:* Tracking how the sale of a product changes month-over-month.
* **Sparklines:** Unlike standard charts, these do **not** include an axis or coordinates. They are used for a quick visual "pulse" check.
    * *Example:* Stock market fluctuations from the opening to the closing of a single trading day.

#### 📊 Comparing Categories
* **Pie Charts:** Use these for a breakdown of an entity into sub-parts. 
    * *Example:* A marketing campaign split by lead source (Social, Paid Ads, Influencers, Events).
* **Bar vs. Column Charts:** * **Bar Charts** are horizontal and excellent for comparing 10+ categories (like population by country).
    * **Column Charts** are vertical and better for showing page views vs. user session time over months.
    * **Stacked Bars:** Useful for "drilling down" within a bar. For example, a single country's population bar split into four different age ranges.

> **⚠️ Warning**
> While Column and Bar charts look similar, they are not always interchangeable. Use **Column Charts** when you need to clearly display negative values or specific "side-by-side" time comparisons.

#### 🗄️ Complex Data & Processes
* **Treemaps:** These are best for nested data. 
    * *Example:* State-wide employment rates. The size of the rectangle represents the population, while the color represents the employment rate.
* **Funnel Charts:** Perfect for visualizing **pipelines**. 
    * *Example:* Measuring conversion rates from the "Lead Generation" stage through to the "Final Sale."

#### 📉 Correlations and Significance
* **Scatter Charts:** Use these to find patterns between two different variables. 
    * *Example:* Viewing product lines by both units sold (volume) and revenue (value).
* **Bubble Charts:** These help in understanding relative significance. 
    * *Example:* Visualizing significant areas of expenditure within a large organization’s sales budget.

> **💡 Tip**
> When using Scatter Charts, remember that **Circle Color** typically represents the category, while **Circle Size** represents the volume/magnitude of the data.

---

### Key Takeaways
- **Continuous Data:** Use Line charts or Sparklines.
- **Proportions:** Use Pie charts or Stacked Bar charts.
- **Hierarchies:** Use Treemaps for nested rectangle visualizations.
- **Processes:** Use Funnel charts to track stages and drop-off rates.
- **Correlations:** Use Scatter or Bubble charts to see how variables relate to one another.

> **✅ Pro Tip**
> Always consider your audience. Bar and Column charts are the most commonly used because they are the most easily understood by non-technical stakeholders.