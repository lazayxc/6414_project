# 6414_project
A regression analysis on factors that impact the divident payout ratio of US listed firms. Modified from the ISYE6414 group project

### Abstract
In the project, we tried to find factors that might affect the dividend payout ratio of US listed firms.

### Why Dividend Payout Ratio?
Dividend payout ratio is a financial metric that represents the proportion of a company's earnings that are distributed to its shareholders in the form of dividends. A high ratio suggests that the company is distributing a significant portion of its earnings to shareholders, leaving less money for reinvestment in the business, while a low ratio indicates that the company is retaining more of its earnings for reinvestment or other purposes. Besides acting as a source of income for shareholders, the dividend payout ratio can also indicate a company's financial health and dividend sustainability. That’s why dividend payout ratio is worth studying.

### Data
We collected the data from [WRDS(Wharton Research Data Services)](https://wrds-www.wharton.upenn.edu/) which includes comprehensive financial data of US listed stocks. We studied  six variables in total, including five quantitative variables — profitability, cash ratio, sales growth, market to book value, debt to equity ratio — and one qualitative variable — industry type. The response variable is dividend payout ratio. The predictor variables are selected according to prior papers in literature. The detailed description and properties of the variables are listed in Table1 as below. 
The data points are time-dependent. Variables, such as sales growth and dividend payout ratio, are calculated annually and may vary from year to year based on a company's performance, market conditions, and other factors. For this project, we choose to conduct regression analysis on S&P 500 index stocks in 2022. 
<div align="center">

| Variables | Definition | Category |
|-----------|------------|----------|
| Profitability | Earnings before interest and taxes/Total assets | quantitative |
| Cash Ratio | Cash and short-term investments/Liabilities | quantitative |
| Sales Growth | (Current sales - Previous sales)/Previous sales | quantitative |
| Market-to-Book Value | Share price beginning of the year/Net asset value per share-basic | quantitative |
| Debt to Equity Ratio | Total liabilities/Equity | quantitative |
| Dividend Payout Ratio | Yearly dividends/Net income after tax | quantitative |
| Industry Type | The industry types include Information Technology, Health Care, Financials, Consumer Discretionary, Communication Services, Industrials, Consumer Staples, Energy, Utilities, and Real Estate. Each industry type will be represented as a dummy variable in the regression model. | qualitative |

<b>Table 1: Data Description</b>

</div>






