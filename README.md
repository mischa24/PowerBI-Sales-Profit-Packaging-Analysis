# 📦 PowerBI Sales, Profit & Packaging Analysis

An interactive Power BI dashboard for comprehensive analysis of sales performance, profitability metrics, shipping costs, and packaging methods across different regions and product categories.

## ✨ Key Features

- **Multi-dimensional analysis** (averages, sums, medians, standard deviations)
- **Dynamic filtering** by Region, Product Category, and Shipping Mode
- **Advanced visualizations** with conditional formatting and interactive slicers
- **Packaging-focused metrics** with container type and delivery cost analysis
- **Drill-down capabilities** across all hierarchical dimensions

---

## 📁 Dataset Overview

The analysis utilizes the following data dimensions:

- **Product Information**  
  - Category & Sub-category hierarchy  
  - Packaging container types  

- **Geographical Data**  
  - Regions & Provinces  

- **Financial Metrics**  
  - Sales, Profit, Discounts  
  - Shipping costs  

- **Logistics**  
  - Ship modes (Standard, Express, etc.)  

---

## 📊 Dashboard Visualizations

### Sales Performance
| Visualization | Description | Screenshot |
|--------------|------------|------------|
| **Average Sales by Sub-category** | Shows normalized sales performance across product types | ![Average Sales](screenshots/Average%20of%20Sales%20by%20Product%20Sub-category.png) |
| **Sales & Profit by Container** | Reveals packaging efficiency metrics | ![Sales Profit](screenshots/Sum%20of%20Sales%20Sum%20of%20Profit%20by%20Product%20Container.png) |

### Profit Analysis
| Visualization | Description | Screenshot |
|--------------|------------|------------|
| **Profit Distribution** | Median and variability analysis by sub-category | ![Profit Stats](screenshots/Median%20and%20StdDev%20of%20Profit.png) |
| **Profit by Sub-category** | Total profitability breakdown | ![Profit Sum](screenshots/Sum%20of%20profit%20by%20Product%20Sub-category.png) |

### Regional Metrics
| Visualization | Description | Screenshot |
|--------------|------------|------------|
| **Product Distribution** | Category prevalence by region | ![Regional Count](screenshots/Count%20of%20Product%20category%20by%20Region.png) |
| **Provincial Sales** | Geographic sales performance | ![Province Sales](screenshots/Sales%20by%20Province.png) |

### Shipping Analysis
| Visualization | Description | Screenshot |
|--------------|------------|------------|
| **Shipping Costs** | Logistics expenses by container type | ![Shipping Cost](screenshots/Sum%20of%20Shipping%20cost%20by%20Container.png) |
| **Ship Mode Distribution** | Transportation method preferences | ![Ship Modes](screenshots/Count%20of%20Ship%20Mode%20by%20Region.png) |

---

## 🛠️ Technical Details

- **Main report file**: `ergasia_3.pbix`
- **Key focus areas**:
  - Packaging type impact on profitability
  - Sub-category performance benchmarking
  - Region-specific KPI analysis
- **File organization**:
  - Screenshots follow descriptive naming conventions
  - `.gitkeep` maintains empty directory structure

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
