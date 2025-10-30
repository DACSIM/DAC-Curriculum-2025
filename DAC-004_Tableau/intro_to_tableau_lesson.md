**Intro to Tableau – 1-Hour Lesson Plan (PowerPoint Outline)**

---

### **Slide 1: Title Slide**
- **Title:** Introduction to Tableau
- **Subtitle:** Turning Data into Insights
- **Instructor:** [Your Name]
- **Agenda:** Basics, Interface, Data, Visuals, Dashboards

---

### **Slide 2: What is Tableau?**
- A **data visualization** and **business intelligence** tool.
- Helps users connect, analyze, and present data visually.
- Used by analysts, marketers, and decision-makers.
- **Goal:** Make data easy to explore and explain.

---

### **Slide 3: Tableau Ecosystem**
- **Tableau Public:** Free, online, public sharing (extracts only)
- **Tableau Desktop:** Full version (supports live and extracts)
- **Tableau Server / Online:** Collaboration and private sharing
- **Tableau Prep:** Data cleaning & preparation tool

---

### **Slide 4: File Types to Know**
| File Type | Description |
|------------|--------------|
| .twb | Workbook only (no data) |
| .twbx | Packaged workbook (includes data) |
| .hyper | Extract file (snapshot of data) |
| .tds / .tdsx | Data source definition (with/without extract) |

---

### **Slide 5: Live vs Extract Connections**
- **Live Connection:** Data updates automatically; needs database access.
- **Extract:** Snapshot of data stored locally as `.hyper` file.
- Tableau Public **only supports extracts**.
- ⚠️ Common error: *"Workbooks saved to Tableau Public must use extracts."*

---

### **Slide 6: Tableau Interface Tour**
- **Data Pane:** Dimensions & Measures
- **Shelves:** Columns, Rows, Filters, Pages, Marks (Color, Size, Label)
- **Show Me:** Suggested chart types
- **Tabs:** Data Source, Sheets, Dashboards, Stories

Include screenshot of Tableau UI (annotated with labels).

---

### **Slide 7: Dimensions vs Measures**
| Type | Meaning | Example |
|------|----------|----------|
| **Dimensions** | Categorical data | Region, Product, Category |
| **Measures** | Quantitative data | Sales, Profit, Quantity |

- Dimensions define *what*, measures define *how much*.
- Show demo: drag [Region] to Columns and [Sales] to Rows.

---

### **Slide 8: Basic Visualizations**
- **Bar Chart:** Compare categories.
- **Line Chart:** Show trends over time.
- **Map:** Geographic insights.
- **Scatter Plot:** Correlation.
- **Tree Map:** Category proportions.

Use an example dataset like *Adidas US Sales* for demos.

---

### **Slide 9: Filters, Sorting, and Grouping**
- **Filters:** Narrow down what data is displayed.
- **Sorting:** Order values ascending/descending.
- **Grouping:** Combine similar categories (e.g., NY + New York).
- Tip: Use *Top N filter* to focus on key performers.

---

### **Slide 10: Calculated Fields**
- Add new metrics based on existing fields.
- **Examples:**
  - `Profit Ratio = SUM([Profit]) / SUM([Sales])`
  - `IF [Profit] > 0 THEN "Positive" ELSE "Negative" END`
- Demo: Create and use a calculated field.

---

### **Slide 11: Building Dashboards**
- Combine multiple sheets into one view.
- Add interactive filters (dropdowns or highlight actions).
- Arrange charts for storytelling.
- Use *floating* vs *tiled* layout options.

---

### **Slide 12: Storytelling in Tableau**
- **Story:** Sequence of dashboards (like a slide deck).
- Each story point = one insight.
- Great for presentations and reports.
- Demo: Create a simple story with 3 dashboards.

---

### **Slide 13: Publishing and Sharing**
- **Public:** Free, but data is visible to everyone.
- **Server / Online:** Private sharing for organizations.
- **Export:** To PDF, image, or PowerPoint.
- Reminder: *Public requires extract format!*

---

### **Slide 14: Common Beginner Mistakes**
- Forgetting to use extracts in Tableau Public.
- Misusing dimensions/measures (e.g., numbers as strings).
- Double aggregation (averaging averages).
- Confusing `.twb` vs `.twbx`.
- Not cleaning data before import.

---

### **Slide 15: Wrap-Up & Q&A**
- **Key Takeaways:**
  - Tableau = visual analytics + storytelling.
  - Extracts are crucial for Tableau Public.
  - Learn to structure data properly.
- **Next Steps:**
  - Try creating a dashboard using sample data.
  - Explore Tableau Public Gallery for inspiration.

---

### **Bonus: Class Demo Ideas**
- Import the *Superstore* dataset.
- Create a Sales by Region bar chart.
- Add a Profit over Time line chart.
- Combine into a dashboard.
- Publish to Tableau Public (show extract step).

