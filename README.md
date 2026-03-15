# Strategic Product Placement Analysis

<div align="center">

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Analyzing the impact of product positioning on retail sales performance using interactive Tableau dashboards.**

[Live Website](https://abhinav-kodes.github.io/Strategic-product-placement/) • [Tableau Public](https://public.tableau.com/app/profile/abhinav.singh/viz/ProductPlacement_17735108523740) • [Dataset](https://www.kaggle.com/datasets/amitvkulkarni/impact-of-product-positioning-on-sales)

</div>

---

## Problem Statement

Retail stores face a critical challenge: **where should products be placed to maximize sales?** This project investigates the relationship between product positioning (Aisle, End-cap, Front of Store), foot traffic, promotions, pricing, and consumer demographics to determine which placement strategies drive the highest average sales volume across three product categories — **Clothing, Electronics, and Food**.

---

## Dataset

| Field | Type | Description |
|---|---|---|
| Product ID | Number | Unique product identifier |
| Product Category | String | Clothing / Electronics / Food |
| Product Position | String | Aisle / End-cap / Front of Store |
| Price | Number | Selling price (avg ~$28) |
| Competitor's Price | Number | Market competitor price (avg ~$25) |
| Promotion | String | Yes / No |
| Foot Traffic | String | High / Medium / Low |
| Sales Volume | Number | Units sold |
| Consumer Demographics | String | College students / Families / Seniors / Young adults |
| Seasonal | String | Seasonal flag |

- **Source:** [Kaggle — Impact of Product Positioning on Sales](https://www.kaggle.com/datasets/amitvkulkarni/impact-of-product-positioning-on-sales)
- **Total Records:** ~1,000 rows
- **Categories:** 3 product categories × 3 positions × 2 promotion states

---

## Visualizations

8 interactive charts were built in Tableau Public:

| # | Chart Title | Type | Key Insight |
|---|---|---|---|
| 1 | Avg Sales Volume vs Product Category | Horizontal Bar | Clothing leads (1,830.1) |
| 2 | Competitor Price vs Price | Grouped Bar | Our price ~10% above market |
| 3 | Sales by Category & Position | Treemap | Clothing @ Front of Store highest (1,923.7) |
| 4 | Consumer Demographics vs Sales | Donut Chart | Balanced across all segments (~443K each) |
| 5 | Product Category vs Price | Pie Chart | Food slightly more expensive (28.47) |
| 6 | Sales by Category & Season/Promotion | Stacked Bar | Promotions consistently boost sales |
| 7 | Foot Traffic by Avg Sales Volume | Bubble Chart | Low traffic areas perform surprisingly well |
| 8 | Promotion Analysis | Text Table | Yes promotions add ~22 avg sales units |

---

## Key Findings

1. **Clothing dominates** — Avg sales of 1,830.1 vs Electronics (1,748.6) and Food (1,727.7)
2. **Front of Store wins** — Clothing at Front of Store = 1,923.7 avg sales (highest across all combos)
3. **Promotions work** — Promoted products average ~1,779 vs ~1,757 without promotions
4. **Low traffic ≠ Low sales** — Aisle Low foot traffic area = 1,900.5 avg sales (highest bubble)
5. **Price premium sustained** — Our avg price ($27–29) exceeds competitor ($25) yet sales hold strong
6. **Demographics are balanced** — No single consumer group dominates; College Students lead slightly (450K)
7. **End-cap underperforms** — Across all categories, End-cap positions show lower sales than Front/Aisle
8. **Food pricing is highest** — At $28.47 avg, Food is priced highest but has lowest avg sales volume

---

## Tech Stack

- **Data Visualization:** Tableau Public
- **Frontend:** HTML5, Bootstrap 5, Google Fonts (Poppins)
- **Hosting:** GitHub Pages
- **Dataset Source:** Kaggle
- **Data Format:** CSV

---

## Repository Structure

```
Strategic-product-placement/
├── index.html          # Main Bootstrap website with embedded Tableau
├── README.md           # This file
└── .nojekyll           # Disables Jekyll for GitHub Pages
```

---

## Running Locally

```bash
# Clone the repo
git clone https://github.com/Abhinav-kodes/Strategic-product-placement.git

# Open in browser
cd Strategic-product-placement
xdg-open index.html       # Linux
open index.html           # macOS
start index.html          # Windows
```

> No build step needed — it's pure HTML with CDN dependencies and live Tableau embeds.

---

## Dashboard Preview

The live dashboard includes:
- **8 interactive Tableau sheets** with all tab navigation
- **3-point Data Story** with guided insights
- **Filters** for Product Category, Promotion, Foot Traffic
- **Responsive layout** for desktop and mobile

**[View Live → abhinav-kodes.github.io/Strategic-product-placement](https://abhinav-kodes.github.io/Strategic-product-placement/)**

---

## Business Recommendations

- **Prioritize Front of Store** placement for all high-margin products
- **Run promotions for Clothing** — highest ROI on already top-performing category  
- **Re-evaluate End-cap strategy** — consistently lowest avg sales across all categories
- **Target College Students** with Electronics at Front of Store (highest demographic segment)
- **Match competitor pricing** on Food category to close the ~$3 gap and boost volume

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

<div align="center">
Made with ❤️ using Tableau Public & Bootstrap 5
</div>
