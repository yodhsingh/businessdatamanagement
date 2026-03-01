# 🥤 STRATEGIC MENU DESIGNING USING DATA-DRIVEN DECISIONS AND INVENTORY MANAGEMENT FOR JUICE BAR SUCCESS 


An empirical investigation into SKU performance, seasonal alignment, and operational momentum for a boutique juice bar. This project leverages data science methodologies to optimize menu architecture and financial predictability.

🗺️ Analysis Workflow

To bridge the gap between raw sales data and executive strategy, the following workflow was implemented:

graph TD
    A[Raw Sales & Cost Data] --> B[Cleaning & SKU Taxonomic Encoding]
    B --> C[Temporal Binning - HCF Method]
    C --> D{Exploratory Data Analysis}
    D --> E[Pareto classification Matrix]
    D --> F[Behavioral Heatmaps]
    D --> G[Holiday Streak Impact Modeling]
    E & F & G --> H[Executive Strategy Roadmap]
    H --> I[Business Growth & Optimization]


📋 Problem Statement

To maintain a cost-efficient, customer-focused enterprise, this research addresses four core objectives:

Seasonal SKU Optimization: Identifying the right products at the right time to match seasonal demand fluctuations.

Smart Sales Strategies: Studying shop off-days to understand customer retention rates.

Inventory Management: Strategic advance purchasing to avoid wastage and lost business opportunities.

Customer Feedback: Designing future menu items and improving offerings based on qualitative insights.

🧪 Methodology & Analysis Framework

2.1 SKU Taxonomic Coding System

Format: [Type][Category][ID]

FP/FB/FS/FH: Food (Patty, Burger, Sandwich, Healthy)

DF/DJ/DM/DS: Drinks (Fruits, Juice, Mocktails, Syrups)

Example: FH01 represents the first unique item in the Healthy Food category.

2.2 Pareto Classification Matrix

Used to identify "Must Keep" vs. "Remove" items based on normalized revenue and unit sales:

Unit Sale \ Revenue

High Revenue

Medium Revenue

Low Revenue

High Unit Sales

Retain/Expand Varieties

Need Price Change

Use in Combos

Medium Unit Sales

Increase Advertising

Core Menu Items

Focus on Price

Low Unit Sales

Offers to Boost Units

Upgrade/Change

Remove/Discontinue

📈 Visualizing EDA & Insights

[!TIP]
Recruiter Note: The following visualizations were generated to identify non-obvious patterns in customer behavior and operational costs.

I. SKU Performance (Pareto Distribution)

Insight: 17 of 44 SKUs generate ~80% of revenue.

Visual: ![Pareto Chart](https://drive.google.com/thumbnail?id=1geJIdNnL2I5F1aQECLeSs0oKn7CEscne&sz=w800)

II. Pricing Sweet-Spot (₹40 Benchmark)

Observation: Significant sales decay observed beyond the ₹40 threshold.

Action: Calibrated pricing to focus on high-volume bundles within this "Goldilocks" zone.

III. Operational Momentum (Holiday Impact)

Discovery: 24-hour closures boost sales by +15% upon return, while 72-hour closures lead to a 10% deficit.

💎 Business Impact: Before vs. After

Metric

Before Analysis

After Data-Driven Strategy

Inventory Strategy

High wastage; frequent stock-outs

Strategic pre-purchasing; 0% seasonal stock-out rate

Menu Composition

Intuitive/Gut-feeling based

Pareto-optimized (Top 17 SKU Focus)

Pricing Model

Static / Industry Standard

Sweet-spot targeted (₹40 benchmark)

Operational Planning

Unpredictable holiday dips

Calculated 24-hr breaks (+15% momentum)

Revenue Target

Fluctuating

Consistent ₹30k/interval target

📂 Project Architecture

├── data/
│   ├── raw_sales_9months.csv
│   └── cost_breakdown.xlsx
├── notebooks/
│   ├── 01_preprocessing_and_binning.ipynb
│   ├── 02_eda_and_pareto_analysis.ipynb
│   └── 03_behavioral_modeling.ipynb
├── visualizations/
│   ├── pareto_sku_distribution.png
│   ├── price_elasticity_curve.png
│   └── holiday_impact_boxplots.png
└── README.md


🚀 Executive Roadmap

Product: Expand top performers (Milk Soda, Mix Juice) into seasonal variants.

Logistics: Transition procurement cycles to Monday/Tuesday for mid-week cash flow recovery.

Marketing: Launch Sandwich-Shake combo architecture based on validated pairing heatmaps.

Singh | Data Science Inquiry | Project Case Study 01
