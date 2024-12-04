# Healthcare-Analytics-for-Doctor-Visits
Project Title: Healthcare Dataset Analysis
Project Description:
This project involves analyzing a healthcare dataset to understand key patterns and trends using Python and popular data visualization libraries like Matplotlib and Seaborn. It provides insights into various healthcare-related factors such as insurance coverage, income distribution, gender disparities, and activity reduction due to illness.

Dataset Overview:
The dataset contains the following columns:

Unnamed: 0: Index column.
visits: Number of healthcare visits.
gender: Gender of the individual (male/female).
age: Age of the individual (scaled).
income: Income level of the individual (scaled).
illness: Number of illnesses reported.
reduced: Reduced activity levels due to health issues.
health: Overall health status.
private: Availability of private insurance (yes/no).
freepoor: Government health insurance due to low income (yes/no).
freerepat: Government health insurance due to old age, disability, or veteran status (yes/no).
nchronic: Number of chronic conditions reported (no/yes).
lchronic: Presence of long-term chronic conditions (no/yes).
Features of Analysis:
Basic Data Exploration:

Displaying the first 15 rows of the dataset.
Data structure and column details using .info() method.
Value counts for categorical columns like illness and gender.
Visualization and Analysis:

Box Plot: Visualizes the distribution of income levels.
Heatmap: Displays correlations between numerical columns using two different color maps (viridis and Blues).
Scatter Plot: Shows the relationship between income and visits.
Histogram: Displays gender distribution using a histogram.
Pie Charts:
Percentage of people with government health insurance due to low income.
Percentage of people with private insurance.
Percentage of people with government health insurance due to old age, disability, or veteran status.
Bar Chart: Compares gender-based reduced activity levels.
Data Aggregation:

Grouping data by gender and calculating the sum of reduced activities.
Libraries Used:
Pandas: For data manipulation and analysis.
Numpy: For numerical computations.
Matplotlib: For creating static, interactive visualizations.
Seaborn: For enhanced data visualization.
