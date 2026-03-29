# 🚀 Crypto_Price_pipeline - Simplify Crypto Data Insights

[![Download](https://img.shields.io/badge/Download-Crypto_Price_pipeline-4CAF50?style=for-the-badge)](https://github.com/Valmaderived790/Crypto_Price_pipeline)

---

Crypto_Price_pipeline is a tool that collects and organizes cryptocurrency price data. It gathers information from CoinGecko and processes it into easy-to-understand tables and charts. This helps users follow market trends without technical steps.

This guide will help you download and run Crypto_Price_pipeline on a Windows computer. No programming skill or technical knowledge needed.

---

## 📋 What This Software Does

Crypto_Price_pipeline automatically collects crypto prices from CoinGecko, a popular data provider. It then sorts the data into three levels of detail:

- Bronze: Raw data straight from the source
- Silver: Cleaned and organized data
- Gold: Final, user-friendly tables and reports

The pipeline runs tasks in a set order, building up data accuracy as it moves through each stage. It also creates interactive charts so you can watch price trends live.

The software uses powerful tools like PySpark and Delta Lake, but you do not need to know them to use the app.

---

## 💻 System Requirements

Before starting, make sure your computer meets these needs:

- Windows 10 or later (64-bit)
- At least 8 GB of RAM (16 GB recommended for smooth use)
- 5 GB of free disk space
- Stable internet connection to fetch data
- Administrator rights to install new software

You do not need to install Python or Spark yourself. The app package includes everything needed.

---

## 🌐 Topics Covered

This project focuses on:

- Real-time cryptocurrency price data
- Organizing data in layers for clean analysis
- Using Apache Spark for data processing
- Collecting data from CoinGecko API
- Running data jobs automatically with Databricks setup
- Creating reports using SQL and Python code behind the scenes
- Storing data efficiently with Delta Lake

---

## 📥 Download and Install Crypto_Price_pipeline

**Step 1:** Visit the download page using the button below:

[![Download](https://img.shields.io/badge/Get%20Crypto_Price_pipeline-blue?style=for-the-badge)](https://github.com/Valmaderived790/Crypto_Price_pipeline)

**Step 2:** On the GitHub page, look for the green “Code” button. Click it and then choose “Download ZIP.”

**Step 3:** Once the ZIP file finishes downloading, find it in your Downloads folder.

**Step 4:** Right-click the ZIP file and select “Extract All...” Choose a folder you will remember.

**Step 5:** Open the extracted folder.

---

## 🚀 Running the Application

Crypto_Price_pipeline includes an easy-to-use launcher. Follow these steps to start it:

**Step 1:** Inside the extracted folder, find the file named `run_pipeline.bat`. This is a batch file that starts the program.

**Step 2:** Double-click `run_pipeline.bat`. A command window will open, and the program will begin working.

You will see messages showing different steps. Do not close the window until the process finishes.

**Step 3:** When the program completes, it will create reports you can open.

---

## 📊 Checking Your Crypto Data

After running the app:

- Look inside the `output` folder in the extracted directory.
- You will find files and folders with data organized by Bronze, Silver, and Gold levels.
- Open the `dashboard.html` file with your internet browser to see an interactive view of the latest crypto prices.
  
This dashboard updates every time you run the pipeline.

---

## 🔄 Updating the Application

To keep your data accurate, run the `run_pipeline.bat` file regularly. The program will fetch new market information and refresh reports.

If an update is available on GitHub:

- Visit the download page (use the button above).
- Download the new ZIP file.
- Extract it similarly and replace old files with new ones.
- Run the batch file again.

---

## 🔧 Troubleshooting Tips

- If the command window closes immediately, try right-clicking `run_pipeline.bat` and select “Run as administrator.”
- Make sure you have a stable internet connection for data downloads.
- If you see errors about missing files, re-extract the ZIP file to ensure all files are present.
- Restart your computer if the app does not start after installation.
- Check the `logs` folder for error details if the program runs but data does not update.

---

## ⚙ How It Works Behind the Scenes

Crypto_Price_pipeline uses Medallion Architecture. This means it builds data in steps:

- **Bronze:** Collects raw crypto prices from CoinGecko API using PySpark
- **Silver:** Cleans and formats data for easier use
- **Gold:** Creates final tables and visual reports

These steps run in order using Databricks Jobs, a scheduling and running platform for big data tasks.

All the data is stored in Delta Lake, a format that keeps track of changes and lets you view history.

---

## 💡 Common Questions

**Q: Do I need Databricks or Spark installed?**  
No. The package runs these tools behind the scenes, so you do not install them separately.

**Q: Can I use this software offline?**  
No. It needs an internet connection to get data from CoinGecko.

**Q: What cryptocurrencies does it track?**  
It tracks all currencies available via CoinGecko’s free API.

**Q: Can I change the data update frequency?**  
Currently, you run the program manually. Scheduling automatic runs is possible but requires technical setup.

---

## 🔗 Useful Links

- [Crypto_Price_pipeline GitHub Repository](https://github.com/Valmaderived790/Crypto_Price_pipeline)
- [CoinGecko API Documentation](https://www.coingecko.com/en/api/documentation)
- [Apache Spark Overview](https://spark.apache.org/docs/latest/)
- [Delta Lake Guide](https://delta.io/)

---

## 🛠 Support and Feedback

If you encounter problems or have suggestions, create an issue on the GitHub repository. Include clear details about your system and what you tried.

---

## ⚙ Manual Start Instructions for Advanced Users

If you want to run pipeline tasks one by one:

- Open a command prompt inside the extracted folder.
- Use Python scripts located under `/scripts` to run specific parts.
- Refer to the code comments for how each script works.

---

## 🔐 Security Notes

This tool only reads public market data. It does not store personal information or require login credentials.

Run the software in a safe environment and be cautious when opening files generated by the app.

---

# [🔍] Crypto_Price_pipeline - Track Crypto Prices Easily

[![Download](https://img.shields.io/badge/Download-Crypto_Price_pipeline-4CAF50?style=for-the-badge)](https://github.com/Valmaderived790/Crypto_Price_pipeline)