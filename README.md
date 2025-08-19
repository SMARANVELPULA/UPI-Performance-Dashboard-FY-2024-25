# UPI-Performance-Dashboard-FY-2024-25

UPI Performance Dashboard 🇮🇳
A comprehensive analysis of UPI transactions in India, providing insights into the digital payments landscape. This dashboard offers a bird's-eye view of the UPI ecosystem, helping to understand the key players and trends shaping the future of digital finance in the country. This project is essential for anyone interested in the Indian fintech scene, from students and researchers to business professionals and policymakers.

**🛠️ Tools Used**
This project was brought to life using a combination of powerful tools:

Advanced Excel: Used for initial data cleaning, manipulation, and validation. Excel's robust features helped in preparing the data for further analysis.

**Python 🐍:** The backbone of our data extraction and processing pipeline.

**Beautiful Soup 🍲**: A Python library for pulling data out of HTML and XML files. It was used for web scraping to collect the raw data from various sources.

**Pandas 🐼: **A powerful data analysis and manipulation library. Pandas was used to clean, transform, and structure the scraped data into a usable format, which was then exported to CSV files.

**Power BI 📊**: A business analytics service by Microsoft. It was used to create an interactive and visually appealing dashboard from the cleaned data. The dashboard allows for easy exploration of the data and helps in identifying key insights.

📖 Understanding the Data
The dataset is divided into four main categories, each in its own CSV file. Here's a breakdown of the terminology used in each file to help you understand the data better:

💳 cleaned_upi_merchant.csv
This file contains data on the types of merchants where UPI transactions are most common.

MCC (Merchant Category Code): A four-digit number assigned to a business by credit card companies. It classifies the business by the type of goods or services it provides. For example, 5411 is the MCC for Groceries and Supermarkets.

Description: A brief explanation of the merchant category.

Volume (Mn): The total number of UPI transactions in millions. So, a value of 3032.59 means there were 3,032.59 million transactions.

Value (Cr): The total value of all transactions in Crores of Indian Rupees. For instance, a value of 64881.98 means ₹64,881.98 Crore was transacted.

🏦 cleaned_upi_psp.csv
This file provides insights into the performance of different Payment Service Providers (PSPs) in the UPI ecosystem. PSPs are the apps you use for UPI payments, like Google Pay, PhonePe, etc.

psp_name: The name of the Payment Service Provider.

Total Volume (Mn): The total number of transactions processed by the PSP in millions.

approved(%): The percentage of transactions that were successfully approved.

BD % (Business Decline): The percentage of transactions that were declined by the business (the merchant's bank).

TD % (Technical Decline): The percentage of transactions that were declined due to technical issues.

Approved Transactions (Mn): The total number of approved transactions in millions.

failed Transactions (Mn): The total number of failed transactions in millions.

failure(%): The overall failure percentage of transactions.

💸 cleaned_upi_remitter.csv
This file contains data about the banks of the people who are sending money (remitters).

UPI Remitter Members: The name of the remitter's bank.

Total Volume (In Mn): The total number of transactions initiated from that bank in millions.

Approved %: The percentage of transactions that were successfully approved.

BD % (Business Decline): The percentage of transactions that failed because of an issue at the beneficiary's (receiver's) end.

TD% (Technical Decline): The percentage of transactions that failed due to a technical issue.

Total Debit Reversal Count (In Mn): The number of times money was debited from the sender's account but the transaction failed, and the money had to be reversed (returned), in millions.

Debit Reversal Success %: The percentage of successful debit reversals. A higher percentage is better, as it means customers get their money back quickly when a transaction fails.

🗺️ cleaned_upi_state.csv
This file provides a state-wise breakdown of UPI transactions.

State / Union Territory: The name of the Indian state or union territory.

Volume (in Mn): The total number of UPI transactions that occurred in that state in millions.

Volume Contribution (%): The percentage of the total national transaction volume that this state contributes.

Value (in Cr.): The total value of all transactions in that state in Crores of Indian Rupees.

Value Contribution (%): The percentage of the total national transaction value that this state contributes.

📈 The Dashboard
The final output of this project is a dynamic and interactive dashboard created in Power BI. The dashboard visualizes all the data from the CSV files, allowing users to:

Compare the performance of different PSPs and banks.

Identify the most popular merchant categories for UPI payments.

Analyze the state-wise distribution of UPI transactions.

Drill down into specific data points for more detailed insights.

The dashboard is designed to be user-friendly and intuitive, making it easy for anyone to explore the fascinating world of UPI data.



🚀 How to Use This Project

Clone this repository 📂

git clone https://github.com/yourusername/upi-performance-dashboard.git

Open the CSV file (upi_stats.csv) to explore raw structured data

Open Power BI file (UPI_Dashboard.pbix) to interact with the dashboard

Explore state-wise trends, KPIs, and visual insights!

Feel free to fork this repository and contribute to the project. Your contributions are always welcome!
