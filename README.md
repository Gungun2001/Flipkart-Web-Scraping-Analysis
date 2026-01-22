<h1>Flipkart Web Scraping, EDA & Power BI Dashboard Project</h1>

<p><strong>Author:</strong> Gungun Agarwal</p>

<hr>

<h2>📑 Table of Contents</h2>
<table border="1" cellpadding="6">
<tr><th>Section</th><th>Link</th></tr>
<tr><td>Overview</td><td><a href="#overview">Overview</a></td></tr>
<tr><td>Business Problem</td><td><a href="#business-problem">Business Problem</a></td></tr>
<tr><td>Dataset</td><td><a href="#dataset">Dataset</a></td></tr>
<tr><td>Tools & Technologies</td><td><a href="#tools">Tools & Technologies</a></td></tr>
<tr><td>Project Structure</td><td><a href="#project-structure">Project Structure</a></td></tr>
<tr><td>Data Cleaning & Preparation</td><td><a href="#data-cleaning">Data Cleaning</a></td></tr>
<tr><td>EDA</td><td><a href="#eda">EDA</a></td></tr>
<tr><td>Dashboard</td><td><a href="#dashboard">Dashboard</a></td></tr>
<tr><td>Key Insights</td><td><a href="#insights">Key Insights</a></td></tr>
<tr><td>Action & Business Impact</td><td><a href="#action">Action & Impact</a></td></tr>
<tr><td>How to Run</td><td><a href="#run">How to Run</a></td></tr>
<tr><td>Final Recommendation</td><td><a href="#recommendation">Final Recommendation</a></td></tr>
<tr><td>Author & Contact</td><td><a href="#contact">Author & Contact</a></td></tr>
</table>

<hr>

<h2 id="overview">📌 Overview</h2>
<ul>
<li>End-to-end Data Analytics project using <strong>Flipkart Air Conditioner data</strong>.</li>
<li>Project covers <strong>Web Scraping → Data Cleaning → EDA → Dashboard</strong>.</li>
<li>Objective is to analyze <strong>pricing, ratings, and product trends</strong>.</li>
</ul>

<h2 id="business-problem">🏢 Business Problem</h2>
<ul>
<li>Customers face difficulty in comparing AC models across brands.</li>
<li>Businesses need insights on competitive pricing.</li>
<li>Lack of clear visibility on rating vs price relationship.</li>
</ul>

<h2 id="dataset">📂 Dataset</h2>
<ul>
<li>Scraped from Flipkart using Python.</li>
<li>Contains product name, brand, price, rating, ton capacity and AC type.</li>
<li>Stored in three Excel files: Raw, Cleaned, and Final.</li>
</ul>

<h2 id="tools">🛠 Tools & Technologies</h2>
<ul>
<li>Python (BeautifulSoup, Requests)</li>
<li>Jupyter Notebook</li>
<li>Microsoft Excel</li>
<li>Power BI</li>
<li>GitHub</li>
</ul>

<h2 id="project-structure">🗂 Project Structure</h2>
<pre>
Flipkart-Web-Scraping-Analysis/
│
├── firstcode.ipynb
├── README.md
│
├── data/
│   ├── Flipkart_Raw_Data.xlsx
│   ├── Flipkart_Cleaned_Data.xlsx
│   └── Flipkart_With_Formulas.xlsx
│
├── dashboard/
│   └── Flipkart_Dashboard.pbix
│
└── screenshots/
    ├── scraping_output.png
    └── dashboard_overview.png
```

---
</pre>

<h2 id="data-cleaning">🧹 Data Cleaning & Preparation</h2>
<ul>
<li>Removed currency symbols from price.</li>
<li>Converted columns to numeric format.</li>
<li>Handled missing values.</li>
<li>Standardized brand and AC type names.</li>
</ul>

<h2 id="eda">📊 Exploratory Data Analysis (EDA)</h2>
<ul>
<li>Brand-wise average price analysis.</li>
<li>Price distribution analysis.</li>
<li>Rating vs price comparison.</li>
<li>Ton capacity based price comparison.</li>
</ul>

<h2 id="dashboard">📈 Power BI Dashboard</h2>
<p><strong>Main Dashboard View:</strong></p>
<img src="screenshots/dashboard_overview.png" alt="Power BI Dashboard Overview" width="900"/>

<p><strong>Dashboard Highlights:</strong></p>
<ul>
<li>Average Price & Rating KPIs</li>
<li>Brand-wise price comparison</li>
<li>Filters for Brand, Ton & AC Type</li>
</ul>

<h2 id="insights">🔍 Key Insights</h2>
<ul>
<li>1.5 Ton ACs are priced higher than other variants.</li>
<li>High price does not always mean higher rating.</li>
<li>Mid-range brands offer the best value for money.</li>
</ul>

<h2 id="action">🚀 Action & Business Impact</h2>
<ul>
<li>Retailers can promote high-rated mid-range AC models.</li>
<li>Pricing strategy can be optimized for 1 Ton and 1.5 Ton segments.</li>
<li>Dashboard helps management make quick data-driven decisions.</li>
<li>Customers can easily compare products using insights.</li>
</ul>

<h2 id="run">▶ How to Run This Project</h2>
<ol>
<li>Clone the repository from GitHub.</li>
<li>Open <code>firstcode.ipynb</code> in Jupyter Notebook.</li>
<li>Run all cells to scrape data.</li>
<li>Review Excel files for EDA.</li>
<li>Open Power BI file to view dashboard.</li>
</ol>

<h2 id="recommendation">✅ Final Recommendation</h2>
<ul>
<li>Focus on value-for-money products.</li>
<li>Use customer ratings as a strong selling point.</li>
<li>Regularly update dashboard for latest trends.</li>
</ul>

<h2 id="contact">👤 Author & Contact</h2>
<p><strong>Gungun Agarwal</strong></p>
<p>Email: <a href="mailto:gunnuagarwal01@gmail.com">gunnuagarwal01@gmail.com</a></p>
<p>LinkedIn: <a href="www.linkedin.com/in/gungun-agarwal-analyst" target="_blank">Visit Profile</a></p>

<hr>
<p>⭐ If you found this project useful, consider giving it a star on GitHub!</p>
