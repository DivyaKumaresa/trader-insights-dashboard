# trader-insights-dashboard
A Power BI dashboard project analyzing trader activity, profit &amp; loss performance, and crypto market sentiment.
# 📊 Trader Intelligence Dashboard

This is a Power BI project that analyzes over 3 lakh trade records and crypto market sentiment to uncover patterns in trading behavior, PnL trends, and emotional market patterns.

## 🧠 Key Insights

🔹 **Trader Overview:**  
- Over 211K traders analyzed; only 32 active  
- HYPE, BTC, and @107 dominate  
- Profit trades far outnumber loss trades

🔹 **PnL Summary:**  
- Net PnL: $13.25M  
- Sell trades yield higher average profit  
- Top coins: @109, ANX, KASH

🔹 **Sentiment Impact:**  
- Higher PnL on Greed Days (Avg 53.88)  
- Sentiment influences trade volume & behavior

## 📷 Dashboard Preview

 Home Page  
 ![](screenshots/home_page.png)![image](https://github.com/user-attachments/assets/e4258651-c401-4ddf-9b90-b677cce25e03)
 PnL Summary 
 ![](screenshots/pnl_summary.png) ![image](https://github.com/user-attachments/assets/adb96ea2-761f-47bd-b18f-770ae14d8018)
  Sentiment View 
![](screenshots/sentiment_view.png) ![image](https://github.com/user-attachments/assets/8b72038f-6b80-48fc-a3ca-7b02dfe6f30c)

## 🛠 Tools Used


- **Power BI** – For data modeling, dashboard creation, and visual storytelling
- **Power Query & DAX ** – For data cleaning, transformation, and merging multiple datasets
 **Excel** – For initial data formatting and manual validation 

## 🧮 Key DAX Formulas Used

NetPnL = SUM('Trades'[Closed PnL])

AvgPnL = AVERAGE('Trades'[Closed PnL])

ProfitTrades = CALCULATE(COUNTROWS('Trades'), 'Trades'[Closed PnL] > 0)

TradeHour = HOUR('Trades'[Timestamp])

## 📁 Files

- `Trader_Analysis.pbix`: Power BI file  
- `screenshots/`: Dashboard images  
- `summary.pdf`: Report slide (optional)

📥 [Download Power BI Project (.zip)]https://drive.google.com/file/d/1aHo37L_9XaiA03KwbBVtVs2X3af3A0/view?usp=sharing  
*Note: Download and extract the `.zip`, then open the `.pbix` file in Power BI Desktop.*

## 👩‍💻 Author

**Divya Kumaresan**  
📧 divyakumaresan2000@gmail.com  
[LinkedIn](https://www.linkedin.com/in/divyakumaresan) 
