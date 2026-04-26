# Experiment-19
# Aim of Experiment:
Real-World and Interactive Visualizations
## Libraries Used
- `pandas` — DataFrame creation and tabular data handling
- `numpy` — Numerical array operations for clustering input data
- `matplotlib.pyplot` — Base plotting engine for static charts
- `matplotlib_venn` — Venn diagram support via `venn2`
- `plotly.express` — High-level Plotly API for Treemap and 3D Scatter plots
- `plotly.graph_objects` — Low-level Plotly API for Sankey and Radar charts
- `scipy.cluster.hierarchy` — Hierarchical clustering via `linkage` and `dendrogram`
- `sys` — Platform detection (`from sys import platform`)
## Plots / Visualizations
- **Treemap** — Displays company department budget distribution using `px.treemap()` with path and values mapped to Department and Budget
- **Dendrogram** — Shows hierarchical clustering of 2D data points using `dendrogram()` with Ward linkage method; X-axis = Data Points, Y-axis = Distance
- **Venn Diagram** — Illustrates set intersection of Set A `{1,2,3,4}` and Set B `{3,4,5,6}` using `venn2()`
- **Sankey Diagram** — Visualizes student flow from Admission → First Year → Second Year → Placed using `go.Sankey()` with node labels and link values `[100, 80, 60]`
- **3D Scatter Plot** — Plots student performance across three axes: Study Hours, Marks, and Attendance using `px.scatter_3d()`
- **Radar Chart (Spider Chart)** — Assesses skill levels across Python, ML, DBMS, DS, and Communication using `go.Scatterpolar()` with `fill='toself'`
## Functions Used
- `pd.DataFrame()` — Creates tabular DataFrame from dictionary
- `px.treemap(df, path, values, title)` — Generates hierarchical treemap chart
- `np.array()` — Creates NumPy array from nested list of 2D data points
- `linkage(data, method='ward')` — Performs hierarchical/agglomerative clustering using Ward's method
- `dendrogram(linked)` — Plots the dendrogram from linkage matrix
- `plt.figure(figsize)` — Sets figure dimensions for matplotlib plots
- `plt.title()` — Sets the chart title
- `plt.xlabel()` — Sets the X-axis label
- `plt.ylabel()` — Sets the Y-axis label
- `plt.show()` — Renders and displays the matplotlib figure
- `venn2([A, B], set_labels)` — Draws a 2-set Venn diagram
- `go.Figure(data)` — Initializes a Plotly figure with trace data
- `go.Sankey(node, link)` — Creates Sankey diagram trace with node labels and link source/target/values
- `px.scatter_3d(df, x, y, z, title)` — Generates interactive 3D scatter plot
- `go.Scatterpolar(r, theta, fill, name)` — Creates polar/radar chart trace
- `fig.add_trace()` — Adds a trace to an existing Plotly figure
- `fig.show()` — Renders and displays the Plotly interactive figure
## Conclusion:
 Demonstrates effective data processing and analysis using Python to extract meaningful information.  

