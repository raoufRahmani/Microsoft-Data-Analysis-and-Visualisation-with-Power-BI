# Case Study Instructions: Create a Sales Report in Power BI

As the data analyst at Adventure Works, creating sales reports is critical to your role. By analyzing sales performance, you can help the company identify trends and areas for improvement, assess business progress, plan resources, and make data-driven decisions.

The sales department has requested a sales report that shows **Adventure Works' sales revenue over time**. The dataset includes fields like **Product Category**, **Product Name**, **Order Date**, and **Total Sales**.

---

## Step 0: Load the Data

* Download and open the provided Power BI file.
* If the data is imported successfully, you will see columns such as **Order Date**, **Order Total**, and **Product Category** in the **Fields** pane on the right side of your screen.

---

## Step 1: Create a Line Chart for Sales Revenue Over Time

1. Select the **Sales Revenue over Time** page.
2. In the **Visualizations** pane (right side of the screen), select the **Line Chart** icon (jagged line).
3. A blank chart will appear on the canvas.
4. In the **Fields** pane, drag:

   * **Order Date > Month** to the **X-Axis**.
   * **Order Total** to the **Y-Axis**.
5. Resize the chart as needed by dragging its edges.

---

## Step 2: Create a Pie Chart for Sales by Product Category

1. Select the **Sales by Product Category** page.
2. In the **Visualizations** pane, select the **Pie Chart** icon.
3. A blank pie chart will appear on the canvas.
4. In the **Fields** pane, drag:

   * **Product Category** to the **Legend**.
   * **Order Total** to the **Values**.
5. Hover over each slice to see tooltips showing the exact sales figures.

---

## Step 3: Create a Stacked Bar Chart for Sales by Day of the Week

1. Select the **Sales by Day of Week** page.
2. In the **Visualizations** pane, select the **Stacked Bar Chart** icon.
3. A blank bar chart will appear on the canvas.
4. In the **Fields** pane, drag:

   * **Order Day of Week** to the **Y-Axis**.
   * **Order Total** to the **X-Axis**.
5. The chart will now display total sales by day of the week.

---

## Step 4: Add a Slicer Visual to Filter Data

1. Stay on the **Sales by Day of Week** page.
2. In the **Visualizations** pane, select the **Slicer** icon.
3. A blank slicer box will appear on the canvas.
4. In the **Fields** pane, drag:

   * **Order Date** to the **Field** well.
5. The slicer now allows you to interactively filter the data by date.
