

#  Urban Micro-Mobility: Customer Demographics & Purchase Behaviour Analysis

Ultimately, the analysis uncovers structural consumer constraints, demonstrating that bike conversion rates are highly dependent on specific commuter parameters rather than general lifestyle choices. The project bridges the gap between raw data sets and high-level corporate data visualization.

---

##  Project Objective
The primary objective of this project was to analyze demographic and socioeconomic profiles of 1,000 consumers to identify the core drivers behind bicycle purchase conversions. By identifying these high-converting customer segments, this analysis provides actionable geographic and demographic target profiles to help a micro-mobility retailer optimize marketing spend and maximize return on investment (ROI).

---

##  Business Questions & KPIs
To evaluate user profiles against purchase conversion, the analysis was structured around three core corporate metrics:

*   **Financial Qualification:** *Does a higher income threshold correlate with conversion?*
    *   **KPI: Customer Acquisition Income Threshold (CAIT)** – Measures the average income benchmark of a converting customer vs. a non-converting prospect.
*   **Geographic Feasibility:** *Does daily commute distance influence the utility and purchase frequency of the product?*
    *   **KPI: Hyper-Local Conversion Density** – Measures the percentage of total sales concentrated within the shortest distance brackets.
*   **Target Segmentation:** *Which lifecycle stage yields the highest volume of successful sales?*
    *   **KPI: Core Demographic Share** – Measures the percentage of total conversions driven by the primary age group.

---

## 🛠️ Data Processing & Hygiene
To transform the noisy, raw demographic data into a corporate-ready reporting state, a strict ETL (Extract, Transform, Load) pipeline was executed using Excel:

*   **Data Standardization:** Shorthand database keys were mapped to human-readable strings (e.g., converting `M`/`S` keys to `Married`/`Single` and `F`/`M` keys to `Female`/`Male`).
*   **String Formatting:** Text values in the commute distance attributes were standardized (e.g., cleaning `10+ Miles` to `More than 10 Miles`) to ensure logical sorting in reporting layers.
*   **Feature Engineering:** Generated a conditional logic attribute (`Age Brackets`) to segment continuous age data into distinct business categories: `Adolescent` (25–30), `Middle Age` (31–60), and `Old` (61+).
*   **Reporting Layer:** Constructed dynamic Pivot Tables and an executive dashboard linking variables to cross-examine customer profiles against final purchase statuses.

---

##  Project Insights
*   **The Income Gap:** Across both genders, buyers consistently sit in higher income brackets. Converting females average **$32,609** (vs. $30,000 for non-buyers), while converting males average **$33,000** (vs. $25,789 for non-buyers). Higher disposable income is a direct statistical driver for this purchase.
*   **The 1-Mile Commute Cliff:** Bike purchase volume experiences a massive drop-off as commute distance increases. **74.4% of all conversions** occur exclusively within the **0–1 mile commute range** (32 out of 43 buyers). Beyond 2 miles, demand almost completely collapses.
*   **Middle-Age Dominance:** The **Middle Age** lifecycle bracket is the definitive powerhouse for this product line, driving **81.4% of total conversions** (35 out of 43 buyers). Conversely, older demographics showed the lowest conversion volume.

---

##  Final Conclusion & Strategic Recommendations
The data proves that this bicycle line does not function as a broad lifestyle or fitness product. Instead, it operates strictly as an **urban micro-mobility solution for affluent, short-range commuters**. 

### Strategic Roadmap for Stakeholders:

1.  **Hyper-Local Targeting:** Reallocate 75% of the digital ad budget away from broad regional marketing and hyper-focus on zip codes within a 1-mile radius of major business districts or transit hubs.
2.  **Demographic Focus:** Tailor creative marketing campaigns specifically toward the "Middle Age" corporate workforce, emphasizing zero-emission short commutes.
3.  **Pricing Policy:** Because buyers cross a higher income threshold, marketing should lean into premium product features rather than aggressive discount
  
  
  

8.  structures.

