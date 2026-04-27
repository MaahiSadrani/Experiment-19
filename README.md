# Experiment-19: Data Analysis and Visualization using Pandas
# Aim:
To perform data analysis using Pandas and visualize insights using Matplotlib and Seaborn.
# Theory:
Data analysis involves inspecting, cleaning, transforming, and modeling data to discover useful information and support decision-making.
1). Pandas - is a powerful Python library used for:
Data manipulation
Data cleaning
Handling missing values
Statistical analysis
Data Visualization
Visualization helps in:
Identifying trends
Understanding relationships
Detecting outliers
## Functions used:
DataFrame – Tabular data structure in Pandas
Data Cleaning – Handling missing or incorrect values
Descriptive Statistics – Mean, median, standard deviation
Grouping Data – Using groupby()
Visualization – Graphical representation of data
# Commands and Code Explanation
1. Importing Libraries
pd: Data handling
np: Numerical operations
plt: Plotting graphs
sns: Advanced visualization
2. Loading Dataset
df = pd.read_csv("data.csv")
Reads CSV file into DataFrame
3. Displaying Data
head() → shows first 5 rows
info() → structure of dataset
describe() → statistical summary
4. Handling Missing Values
df.isnull().sum()
df.dropna()
df.fillna(method='ffill')
Checks and handles missing data
5. Selecting Data
Access specific rows and columns
6. Filtering Data
Filters rows based on condition
7. Grouping Data
Groups data and calculates mean
8. Sorting Data
Sorts dataset

# Conclusion:
In this experiment, data analysis was performed using Pandas, including data cleaning, filtering, grouping,
and statistical analysis. Various visualization techniques using Matplotlib and Seaborn were implemented to better
<img width="1564" height="554" alt="Screenshot 2026-04-27 092823" src="https://github.com/user-attachments/assets/efb398da-2d8d-4ab9-aa9c-5e48ed68dd6f" />
<img width="690" height="511" alt="Screenshot 2026-04-27 092852" src="https://github.com/user-attachments/assets/70a0728f-8671-4d12-b17d-158d590b55de" />
<img width="679" height="542" alt="Screenshot 2026-04-27 092904" src="https://github.com/user-attachments/assets/d2a9dbf0-88b9-4962-a9b0-2d958d688d82" />
<img width="1546" height="552" alt="Screenshot 2026-04-27 092927" src="https://github.com/user-attachments/assets/544ec93d-4b9d-452a-93e0-3f43848911c4" />
<img width="1058" height="590" alt="Screenshot 2026-04-27 093002" src="https://github.com/user-attachments/assets/a9b839cf-e909-4233-9902-855f6238a014" />
<img width="685" height="571" alt="Screenshot 2026-04-27 093023" src="https://github.com/user-attachments/assets/aa72778f-147d-45f7-8514-b8b896d788b2" />
understand the dataset. The experiment demonstrates how raw data can be transformed into meaningful insights using analysis and visualization tools.
