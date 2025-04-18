# 🦄 Unicorn Companies Data Analysis

> This project was completed as part of my scholarship in the Data Science program at the Artificial Intelligence and Technology Academy. It was undertaken within the scope of the "Go Beyond the Numbers: Translate Data into Insights" chapter of the Google Advanced Data Analytics course.

## 📊 Overview

This project explores a dataset of unicorn companies—privately held startups valued at over $1 billion—as of March 2022. The objective is to analyze the dataset using basic Python and data visualization tools to extract insights, identify trends, and enhance data literacy through hands-on experience with real-world business data.

## 📁 Dataset

- **Name:** `Unicorn_Companies.csv`
- **Source:** Kaggle
- **Rows:** 1,074 unicorn companies
- **Columns:** 10 (including company name, valuation, funding, industry, investors, etc.)

### Key Columns:

- `Company`: Name of the unicorn company  
- `Valuation`: Company valuation (in billions)  
- `Date Joined`: Date the company became a unicorn  
- `Industry`: Business industry  
- `Funding`: Total funding raised  
- `Year Founded`: Year the company was founded  
- `Select Investors`: Top investors  
- `Country/Region`, `Continent`, `City`: Geolocation details  

## 🛠 Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

## 🧪 Key Tasks

- Import and explore the dataset
- Data cleaning (e.g., converting date and valuation fields)
- Create new calculated fields such as:
  - Time to reach unicorn status
  - Numeric valuation column
- Sampling for analysis
- Visualizations:
  - Time to reach unicorn status by industry
  - Maximum valuation per industry

## 📈 Example Insights

- Some companies took decades to reach unicorn status, while others did so in just a few years.
- Industries like fintech and e-commerce tend to dominate in terms of both number of unicorns and highest valuations.
- Investment strategies could benefit from understanding time-to-unicorn trends by industry.

## ✅ Outcome

By the end of this project, we were able to:

- Practice EDA (Exploratory Data Analysis) techniques
- Apply data transformation and visualization skills
- Derive meaningful insights from startup valuation trends

## 📌 How to Run

1. Clone the repository  
2. Open the Jupyter Notebook file  
3. Ensure that `Unicorn_Companies.csv` is in the same directory  
4. Run the notebook step-by-step

```bash
git clone https://github.com/gumaruw/unicorn-companies-analysis.git
cd unicorn-companies-analysis
jupyter notebook
```

## ⚖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
