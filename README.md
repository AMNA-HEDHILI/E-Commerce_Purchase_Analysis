# E-commerce Purchases Analysis

Exploratory data analysis of 10,000 e-commerce purchases: how customers spend, when they buy, which customer segments differ, and whether those differences are real or just noise.

## Goal
Answer practical customer questions (spending, timing, card provider, language, job, browser) and use statistical tests to separate real patterns from random variation.

## Dataset
Synthetic e-commerce purchases dataset (public practice data, 10,000 rows). It contains fields such as card details, emails, and IP addresses.Sensitive columns are dropped in the notebook and never displayed.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, SciPy, Jupyter Notebook

## What I did
- **Data quality:** missing values, duplicates, purchases with a price of 0
- **Privacy:** removed card numbers, security codes, emails, IP addresses and addresses after building the features I needed
- **Feature building:** email domain, card expiry year, browser, operating system, price bands
- **Spending:** distribution of purchase price and share of purchases by price band
- **Timing:** AM vs PM comparison with a t-test
- **Segments:** average spend by card provider, language, operating system and job
- **Statistical checks:** ANOVA to test whether differences between groups are real


## Limitations
- The data is synthetic, so real business conclusions cannot be drawn from it.
- Only one price per customer is available, with no purchase history or product information.

## How to run
1. Install the packages: `pip install pandas numpy matplotlib seaborn scipy`
2. Put `Ecommerce Purchases.csv` in the same folder as the notebook
3. Open `Ecommerce_Purchases_Analysis.ipynb` and run all cells

## Author
Amna Hedhili: [LinkedIn](https://linkedin.com/in/amna-hedhili-07185a201) | [GitHub](https://github.com/AMNA-HEDHILI)
