# Data_Visualization_Roadmap
Data Visualization: What it is , Why it’s so Important & How to Use It :

Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

Why its so important ? Data visualization provides a quick and effective way to communicate information in a universal manner using visual information. The practice can also help businesses identify which factors affect customer behavior; pinpoint areas that need to be improved or need more attention; make data more memorable for stakeholders , understand when and where to place specific products; and predict sales volumes.

With the Pandas, Seaborn and Matplotlib we can easily plot different types of charts, graphs and maps.

Let us break the chart types into three broad categories : –

Trends :- A trend is defined as a pattern of change.
  sns.lineplot – Line charts are best to show trends over a period of time, and multiple lines can be used to show trends in more than one group.

Relationship :- There are many different chart types that you can use to understand relationships between variables in your data.
  sns.barplot – Bar charts are useful for comparing quantities corresponding to different groups.
  sns.heatmap – Heatmaps can be used to find color-coded patterns in tables of numbers.
  sns.scatterplot – Scatter plots show the relationship between two continuous variables; if color-coded, we can also show the relationship with a third categorical variable.
  sns.regplot – Including a regression line in the scatter plot makes it easier to see any linear relationship between two variables.
  sns.lmplot – This command is useful for drawing multiple regression lines, if the scatter plot contains multiple, color-coded groups.
  sns.swarmplot – Categorical scatter plots show the relationship between a continuous variable and a categorical variable

Distribution :– We visualize distributions to show the possible values that we can expect to see in a variable, along with how likely they are.
  sns.distplot – Histograms show the distribution of a single numerical variable.
  sns.kdeplot – Kernal Density Estimate KDE plot (or 2D KDE plots) show an estimated, smooth distribution of a single numerical variable (or two numerical variables).
  sns.jointplot – This command is useful for simultaneously displaying a 2D KDE plot with the corresponding KDE plots for each individual variable.
