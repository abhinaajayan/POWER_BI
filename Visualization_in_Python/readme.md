# Python For Data Visualization – Notes

Python visualization is used to represent data graphically.  
It helps in exploring, understanding, and presenting data patterns.  
It works well with data analysis libraries like **Pandas** and **NumPy**.

---

## 1️⃣ Popular Libraries

| Library                  | Purpose                     | Key Features |
|--------------------------|----------------------------|--------------|
| **Matplotlib**           | Basic plotting             | Line, bar, scatter, pie charts; highly customizable |
| **Seaborn**              | Statistical visualization  | Heatmaps, boxplots, violin plots, correlation analysis |
| **Plotly**               | Interactive visualization  | Zoomable, web-ready, dashboards |
| **Pandas Visualization** | Quick plotting             | `df.plot()` for line, bar, histogram |
| **Altair**               | Declarative, concise       | Grammar-of-graphics style, interactive plots |
| **Bokeh**                | Web visualization          | Interactive dashboards for web apps |

---

## 2️⃣ Basic Plot Types

| Plot           | Use Case |
|----------------|----------|
| **Line Plot**  | Trend over time |
| **Bar Chart**  | Compare categories |
| **Histogram**  | Distribution of values |
| **Boxplot**    | Outliers, median, quartiles |
| **Scatter Plot** | Relationship between two variables |
| **Heatmap**    | Correlation or matrix visualization |
| **Pie Chart**  | Percentage composition |

---

## 3️⃣ Matplotlib Basics

**Matplotlib** is a basic plotting library for Python.  

### Line Plot

```python
import matplotlib.pyplot as plt

plt.plot([1, 2, 3, 4], [10, 20, 25, 30])
plt.title("Line Plot Example")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()
