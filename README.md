[Click Here to View Project](https://colab.research.google.com/drive/116WzDZpyh0p724WdAyHnZkZhj7eE-Tdi)

# Physical Activity, BMI and Type 2 Diabetes

**Data Science Fundamentals Project** | Python, Pandas, Scikit-learn, Data Visualisation

## About the Project

This project explores the relationship between physical activity, BMI and Type 2 diabetes. Our main research question was:

> To what extent does physical activity reduce the likelihood of Type 2 diabetes across different BMI categories?

We used three health and lifestyle datasets and followed the data science process from data preparation and analysis to visualisation and recommendations.

## My Contributions

### Prepare

I was involved in evaluating one of the datasets before deciding whether it was suitable for our research question.

I looked at the availability and quality of variables such as BMI, physical activity, age and diabetes status. I also explored the distribution of the variables and considered potential issues such as missing data, self-reporting bias, age differences and underrepresentation of certain BMI groups.

This helped me realise that choosing a dataset is not just about whether it contains the variables we need. We also need to think about how the data was collected and whether the dataset is representative enough for the question we are trying to answer.

### Process

I worked on preparing one of the datasets for the later analysis. This included selecting the relevant variables, cleaning the diabetes categories, standardising the column names and categorising BMI, age and physical activity.

One of the challenges was that physical activity was measured differently across the datasets. I had to standardise the measurements so that the datasets could eventually be combined and compared.

This part of the project taught me that data cleaning is not just about removing missing values or fixing errors. There are also a lot of decisions involved in deciding how variables should be grouped and transformed.

### Analyse

I worked on both the descriptive and prescriptive parts of the analysis.

For the descriptive analysis, I looked at the relationship between physical activity, BMI and Type 2 diabetes using statistical analysis and visualisations. We used methods such as Spearman correlation, chi-square testing, Logistic Regression and Decision Trees.

For the prescriptive analysis, I used the Logistic Regression model to simulate what would happen to predicted diabetes risk if an individual changed their physical activity level from Low to High.

The model showed a **10.26 percentage-point reduction in predicted Type 2 diabetes risk** overall. When comparing BMI groups, the largest simulated reduction was among the **Overweight group at 12.79 percentage points**.

These results are based on model predictions and should not be interpreted as proof that increasing physical activity directly causes this exact reduction in diabetes risk.

### Share

I also worked on the visualisation and presentation of our findings. I focused on making the results easier to understand, particularly how predicted diabetes risk changed across different physical activity and BMI groups.

This made me realise that visualisation is not just about making graphs look good. The way information is presented can make it much easier for someone to understand the main findings and patterns in the data.

## Key Takeaways

Some of the main things I learnt from this project were:

- How to assess whether a dataset is actually suitable for a research question.
- How to clean and standardise data from different sources.
- How choices made during data preparation can affect the analysis.
- How to use statistical tests and machine learning models to investigate relationships in data.
- The difference between descriptive analysis and using a model for "what-if" scenarios.
- The importance of being careful when interpreting associations from observational data.
- How to communicate data findings through clear visualisations.

Overall, this project gave me a better understanding of how the different stages of a data science project fit together. I also learnt that data science is not just about building a model. A large part of the work involves understanding the data, making sensible decisions during preparation, interpreting the results carefully and communicating them clearly.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Google Colab
