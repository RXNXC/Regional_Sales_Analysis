# Regional_Sales_Analysis
A structured business intelligence project analyzing 1,500 sales orders across 5 regions, 6 salespersons, and 3 promotional campaigns using Microsoft Excel.

Overview

This project answers four business questions from a product sales dataset containing 19 fields — covering regional revenue, salesperson performance, promotion effectiveness, and delivery logistics.

Business Questions
- Revenue by Region — Which region generates the highest revenue, and how does customer type (Retail vs. Wholesale) affect the breakdown?
- Salesperson Performance — Who leads in sales volume, and who has the lowest return rate?
- Promotion Effectiveness — Do promotions drive higher order value, or do discounts simply erode margins?
- Delivery Analysis — Which region is slowest, and which has the most delayed orders?

Deliverables
- Product_Sales_Analysis.xlsx — Five-sheet workbook with a KPI overview dashboard, one analysis sheet per question, formatted summary tables, and embedded combo/bar charts
- Sales_Analysis_Process_Documentation.docx — Full methodology document explaining every metric, formula, and visualisation choice across all four questions

Tools & Methods
Tool	Usage
- Excel:	Power Query, Pivot tables, DAX measures
- Excel Charts: Clustered bar, clustered column, combo (column + line)
- Date Arithmetic- 	Derived Delivery Days column from OrderDate and DeliveryDate

Word	Structured process documentation with colour-coded formula rationale

Key Findings
- North leads all regions in revenue ($967,958) with Retail as the dominant customer type
- Bob generates the highest revenue ($796,781); Eva has the lowest return rate (21.6%)
- FREESHIP is the most effective promotion — highest AOV ($2,955), highest revenue ($1.24M), and no direct margin cut
- North has the highest delivery delay rate (52.75%); Central is the most efficient region (5.88 avg days)

Folder Structure
product-sales-regional-analysis/
│
├── 📂 data/
│   └── Product-Sales-Region.xlsx          # Raw dataset (1,500 orders, 19 columns)
│
├── 📂 analysis/
│   └── Product_Sales_Analysis.xlsx        # Full workbook — dashboard + 4 analysis sheets
│
├── 📂 documentation/
│   └── Sales_Analysis_Process_Documentation.docx  # Methodology & formula rationale (Word)
│
├── 📂 assets/
│   └── screenshots/                       # Dashboard and chart previews (optional)
│       ├── overview_dashboard.png
│       ├── q1_revenue_by_region.png
│       ├── q2_salesperson_performance.png
│       ├── q3_promotion_analysis.png
│       └── q4_delivery_analysis.png
│
└── README.md

How to Use
- Clone or download the repository
- Open data/Product-Sales-Region.xlsx to explore the raw dataset
- Open analysis/Product_Sales_Analysis.xlsx to view the full analysis workbook — navigate sheets using the tabs at the bottom
- Open documentation/Sales_Analysis_Process_Documentation.docx for a step-by-step explanation of every metric and formula used

Author
Akinwale Adewale David
📧 adewaledave4@gmail.com · 🔗 LinkedIn . https://rxnxc.github.io
