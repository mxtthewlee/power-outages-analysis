# Power Outages in the United States

**Name:** Matthew Lee  
**Course:** DSC 80 — UC San Diego  
**Website:** [View Final Website](https://mxtthewlee.github.io/power-outages-analysis/)

---

## 🔍 Research Question

**What types of power outages tend to affect the highest number of people, and how do these types differ by region?**

This project investigates how different categories of power outages (e.g. weather-related, equipment failure) impact populations across U.S. regions, using data from 2000 to 2016. The goal is to identify patterns in outage severity and examine regional vulnerability.

---

## 🧹 Data Cleaning

We began by cleaning the dataset to:
- Remove metadata/header artifacts
- Convert columns to numeric types (e.g. customers affected)
- Drop rows with missing or invalid values

---

## 📊 Exploratory Data Analysis

We explored distributions of:
- Outage causes and sub-causes
- Regional frequency and severity
- Customers affected by outage type

---

## 📈 Key Visualization

<iframe src="assets/customers_by_cause_and_region.html" width="100%" height="600" frameborder="0"></iframe>

This interactive plot shows how the number of customers affected varies by outage type and region. Weather-related causes are the most impactful overall, with certain regions more prone to specific types.

---

## 🤔 Conclusion

Weather is the leading cause of power outages that affect large populations. However, regional differences are significant — for example, the MRO and SERC regions experience more outages due to natural causes, while WECC regions show a broader mix of causes.

Understanding these patterns can help utilities and policymakers target infrastructure investments and disaster preparedness efforts more effectively.

---

## 💻 Technologies Used
- Python (Pandas, Plotly, Matplotlib)
- Jupyter Notebook
- GitHub Pages

---

## 📁 Files

- `template.ipynb`: Main analysis notebook
- `assets/customers_by_cause_and_region.html`: Interactive bar chart
- `_config.yml`: GitHub Pages theme config
