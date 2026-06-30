# Men's Fashion Brand Sales Analysis Dashboard

### Dashboard Link: https://app.powerbi.com/groups/me/reports/1e320d2a-c46d-4202-a627-53b0c3f443eb/5f8572048bfcf6fb26c1?experience=power-bi



---

## Problem Statement

This dashboard helps retail businesses, fashion brands, merchandising teams, and sales analysts understand brand performance by analyzing product pricing, discounts, profit margins, and product variety across multiple men's fashion brands. It provides valuable insights into pricing strategies, discount distribution, sales performance, and brand profitability, enabling decision-makers to evaluate overall business performance and identify opportunities for revenue growth.

The report consolidates key retail performance indicators into a single interactive dashboard, allowing users to compare brands based on average sales price, discount percentage, profit percentage, and product assortment. Through interactive filters and visualizations, users can analyze individual brands, compare high-performing and low-performing products, and identify pricing trends across the fashion retail market.

By monitoring brand-wise sales metrics, discount strategies, and profitability trends, businesses can optimize pricing decisions, improve promotional campaigns, identify premium brands, and maximize overall profit margins. The dashboard serves as a comprehensive business intelligence solution for understanding retail performance and supporting data-driven merchandising decisions.

---

## Steps Followed

* **Step 1 :** Load the men's fashion retail dataset into Power BI Desktop. The dataset contains brand information, product details, sales prices, discount percentages, profit percentages, product categories, and other retail-related attributes.

* **Step 2 :** Open Power Query Editor and inspect the dataset for data quality by verifying column names, reviewing data types, checking missing values, and ensuring overall data consistency before designing the report.

* **Step 3 :** It was observed that the dataset contains information related to fashion brands, product pricing, discounts, profit percentages, product varieties, categories, and other sales-related metrics used for retail performance analysis.

* **Step 4 :** Required data type conversions were performed to ensure numerical, categorical, and text fields were correctly recognized by Power BI for accurate calculations and visualizations.

* **Step 5 :** The dataset was cleaned by handling missing values, correcting inconsistencies, and preparing the data through Power Query transformations before loading it into the data model.

* **Step 6 :** After completing all necessary transformations, the cleaned dataset was loaded into Power BI Desktop.

* **Step 7 :** A custom report theme with a dark navy and gold color palette was applied under the **View** tab to provide a premium and visually consistent dashboard experience.

* **Step 8 :** Appropriate relationships between the tables were verified within the data model to ensure accurate calculations and seamless interaction across all report visuals.

* **Step 9 :** Multiple calculated columns and DAX measures were created to calculate important retail KPIs including Average Sales Price, Average Discount Percentage, Average Profit Percentage, Brand Variety Count, and other performance metrics used throughout the report.

* **Step 10 :** Multiple analytical visuals were added to summarize brand performance and compare key retail indicators across different fashion brands.

* **Step 11 :** Interactive slicers were incorporated to allow users to dynamically filter the report by available fashion brands and analyze individual brand performance.

The slicers include:

(a) Brand Name

These slicers allow users to interactively explore sales performance and compare different brands throughout the dashboard.

* **Step 12 :** Various visualizations were created to analyze multiple business perspectives including:

- Clustered Bar Charts
- Area Charts
- Donut Charts
- Pie Charts
- Interactive Cards
- Brand Selection Panel

These visuals help users identify the highest-performing brands, compare discount strategies, analyze product variety, evaluate average sales prices, and monitor brand profitability.

* **Step 13 :** Interactive filtering and cross-highlighting were enabled across all visuals, allowing users to drill down into individual brand performance by selecting any chart or slicer.

* **Step 14 :** Separate report pages were designed to provide different analytical perspectives of the retail dataset:

- Brand Selection Page
- Brand Performance Dashboard

Each report page focuses on a different business objective while maintaining consistent navigation and dashboard formatting.

* **Step 15 :** Business KPIs were calculated using DAX measures to monitor average selling prices, brand profitability, product variety, and promotional discount performance.

* **Step 16 :** Dynamic visual interactions were configured so that selecting any visual automatically filters all related charts, enabling detailed exploration of individual brands and performance metrics.

* **Step 17 :** Appropriate formatting, titles, legends, labels, tooltips, color themes, icons, and layout adjustments were applied to improve dashboard readability and enhance the overall user experience.

* **Step 18 :** The completed report was published to **Power BI Service**, allowing users to securely access, interact with, and share the dashboard online.
* **Step 19 :** Several DAX measures were created to calculate key retail business metrics used throughout the dashboard.

Following DAX expressions were written for the same,

---

## Top 5 Brands by Average Discount %

A clustered bar chart was designed by applying the **Average** aggregation on the **Discount Percentage** field and a **Top N** filter to display the five brands offering the highest average discounts.

This visual helps businesses compare promotional strategies and identify brands providing the largest customer discounts.

---

## Top 5 Brands by Highest Average Profit %

An area chart was designed using the **Average Profit Percentage** for each brand to identify the five most profitable brands.

This visualization enables decision-makers to evaluate profitability across different fashion brands.

---

## Top 5 Brands by Highest Average Sales Price

A clustered column chart was designed to compare the **Average Sales Price** of different brands and highlight the five premium-priced brands.

This visual helps users compare pricing strategies and identify premium brands within the men's fashion market.

---

## Top 5 Brands by Highest Number of Varieties

A donut chart was created to display the **Top 5 Brands** having the highest number of product varieties.

This analysis provides insights into product assortment and inventory diversity across brands.

---

## Bottom 5 Brands by Average Profit %

A pie chart was designed to identify the **Bottom 5 Brands** based on Average Profit Percentage.

This visual helps businesses recognize comparatively low-performing brands for further profitability analysis.

---

### Brand Selection Filter

A dynamic brand selection panel was incorporated to enable users to interactively filter the dashboard by individual brands. Selecting any brand automatically updates all report visuals, providing detailed brand-level performance analysis.

---

* **Step 20 :** Multiple report pages were designed to provide comprehensive retail business analysis.

The report contains two interactive dashboard pages:

(a) Brand Selection Page

(b) Brand Performance Dashboard

Each report page provides a different analytical perspective while maintaining consistent navigation, branding, and interactive filtering capabilities.

---

* **Step 21 :** After completing dashboard development, validation, and testing, the report was published to **Power BI Service** for secure online access and interactive business reporting.

# Snapshot of Dashboard (Power BI Service)

```markdown
![Power BI Service Dashboard](YOUR_GITHUB_POWERBI_SERVICE_IMAGE_LINK)
```

---

# Report Snapshot (Power BI Desktop)

### Brand Selection Page

```markdown
![Dashboard 1](https://github.com/2024ceb1051-beep/First/blob/5d657aa6f6ddceaf7f77fdbf5a6a4eb81e839504/Screenshot%202026-06-29%20183312.png)
```

---

### Brand Performance Dashboard

```markdown
![Dashboard 2](https://github.com/2024ceb1051-beep/First/blob/5d657aa6f6ddceaf7f77fdbf5a6a4eb81e839504/Screenshot%202026-06-29%20225442.png)
```
# Insights

A two-page interactive retail analytics report was created on Power BI Desktop and was later published to Power BI Service.

Following inferences can be drawn from the dashboard;

---

### [1] Overall Brand Performance

The dashboard provides a comprehensive overview of brand performance by comparing average sales price, discount percentage, profit percentage, and product variety across multiple men's fashion brands.

Users can quickly identify premium brands, highly discounted brands, and brands with lower profitability using interactive visualizations.

---

### [2] Discount Analysis

* The dashboard highlights the **Top 5 Brands by Average Discount Percentage**.

* Brands offering the highest average discounts can be easily identified and compared.

* Discount analysis helps businesses evaluate promotional strategies and understand how different brands position themselves in the market.

* These insights support better pricing decisions and campaign planning.

---

### [3] Profitability Analysis

* The report identifies the **Top 5 Brands by Highest Average Profit Percentage**.

* It also highlights the **Bottom 5 Brands by Average Profit Percentage**, enabling users to recognize brands with comparatively lower profit margins.

* Comparing highly profitable and low-profit brands allows decision-makers to evaluate pricing efficiency and optimize business strategies.

---

### [4] Sales Price Analysis

The dashboard compares brands based on their **Average Sales Price**, helping businesses identify premium-priced brands within the men's fashion market.

* Premium brands generally command higher average selling prices.

* Brand-wise pricing comparison assists retailers in evaluating market positioning and pricing competitiveness.

* These insights support strategic pricing decisions across different product brands.

---

### [5] Product Variety Analysis

The dashboard analyzes product assortment by displaying the **Top 5 Brands with the Highest Number of Product Varieties**.

* Brands with a larger product portfolio offer customers greater purchasing choices.

* Comparing product variety helps identify brands with extensive collections and stronger market presence.

* Product assortment analysis can support inventory planning and merchandising decisions.

---

### [6] Brand Comparison

The dashboard enables users to compare multiple performance metrics simultaneously for different fashion brands.

Business users can analyze:

* Average Sales Price

* Average Discount Percentage

* Average Profit Percentage

* Number of Product Varieties

This comparative analysis helps identify high-performing brands and benchmark business performance across competitors.

---

### [7] Interactive Brand Filtering

The report includes an interactive **Brand Selection Page** containing a comprehensive list of available brands.

Users can:

* Select individual brands.

* Compare multiple brands.

* Instantly filter all report visuals.

* Perform detailed brand-level performance analysis.

This interactive navigation provides a seamless analytical experience for business users.

---

### [8] Dashboard Features

The report includes multiple interactive business intelligence features including:

* Brand Selection Panel

* Dynamic Cross Filtering

* Interactive Charts

* Donut Chart

* Pie Chart

* Bar Charts

* Area Charts

* Custom Dashboard Theme

These features enable users to explore retail performance from multiple analytical perspectives while maintaining an intuitive user experience.

---

### [9] Business Outcome

Using this dashboard, business users can:

* Compare the performance of different fashion brands.

* Identify brands offering the highest average discounts.

* Evaluate profitability across multiple brands.

* Analyze average selling prices for premium and budget brands.

* Compare product variety between brands.

* Support merchandising and pricing decisions.

* Optimize promotional campaigns using discount analysis.

* Make data-driven business decisions through interactive retail analytics.

Overall, this dashboard provides a comprehensive retail business intelligence solution for analyzing men's fashion brands, enabling retailers, merchandising teams, and business analysts to evaluate pricing strategies, profitability, product assortment, and overall brand performance through interactive visualizations and data-driven insights.
