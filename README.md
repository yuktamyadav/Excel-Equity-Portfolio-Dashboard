# 📊 Excel Equity Portfolio Dashboard

## 📌 Description

Recently I built a financial data analytics dashboard which can be used to analyse data or key metrics that help in Stock Portfolio's assessment as well as in decision making. This Dashboard can be a crucial analytical tool for an Investor (in American Equity or Stock Market) to store the information related to his or her stock holdings, statistically compare different equity holdings across metrics such as Price, Breakdown, Volume, Profit/Loss, Market Value, etc. Several visualization charts are also used for the same purpose. It can help an investor to - rationalize his portfolio, and assess future investment decisions.

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- **Excel** – Main platform used for data analysis, report and dashboard building
- **Data Visualizations** – To visualize stock portfolio, gain or loss and historical performance
- **Charts** – To visualize the data in the Liquidations Database
- **Data Validation** – Used as a drop-down filter for Stock Lookup and Comparison
- **File Formats** – `.xlsx` for development and `.png` for dashboard previews
- **Stock Ticker** – Utilized for compiling several data atrributes for a particular stock

## 🗄️ Dataset

The dataset represents a particular individual's equity asset holdings or liquidations, provided in Excel format. The dataset consists of 1 fact table structured as follows:

**Transactions Table**
- Columns: Date, Equity/Stock, Ticker, Transaction Type, Units, Price, Total Transaction Amount (Market Value), Currency

## 💡 Features / Highlights

The core portfolio dashboard is situated in the Main Sheet, which consists the data for Current Stock Holdings, sourced out from the Transactions Table in the Transactions Sheet, using Stock Ticker. It has various key attributes for a live stock holding which are mentioned below. Apart from this, The chart visualizations as well as the Data Validation dialogue also exists on the same sheet. There's an additional sheet named Charting, which consists of the Historical Comparison chart for two different equities. This sheet contains historical price data of a stock for a selected period of month, which is consolidated using the STOCKHISTORY and EDATE Functions along with the Ticker Symbol.

### 💱 The Dashboard contains Stock Data from the following American Stock Exchanges -

1. **NASDAQ** :  National Association of Securities Dealers Automated Quotations
2. **NYSE** : New York Stock Exchange

### 💲 Key Data Attributes for Current Stock Holdings -

1. Company/Equity
2. Ticker
3. Industry
4. Quantity of Shares
5. Price
6. Equity Market Value
7. Breakdown in %
8. Daily Change in Holding's Value
9. Gain/Loss
10. 52 Week High/Low

### 📊 Analytical Visualizations -

1. **Portfolio Breakdown** : Pie Chart
2. **Gain/Loss** : Clustered Column Chart
3. **Historical Performance** (To compare Prices of two different stocks) : Line Chart

## 🖼️ Project Snapshot

![Image Alt](https://github.com/yuktamyadav/Excel-Equity-Portfolio-Dashboard/blob/a33128ab993c3622b1cb5922ce6a640e3efc304b/Equity%20Portfolio%20Dashboard.png)
