# 📌 Project Overview

This project involved designing and developing a comprehensive **Supply Chain Dashboard** using a custom Samsung dataset. The objective was to transform raw supply chain data into actionable business insights, providing end-to-end visibility from supplier procurement to final customer delivery.

The project was divided into two phases:

## Part 1: Backend Development

* Dynamic data import and transformation
* Star schema data modeling
* Core DAX measure creation
* High-level supply chain overview dashboard

## Part 2: Advanced Analytics & Storytelling

* Supplier analysis
* Inventory & Production analysis
* Shipment analysis
* Customer analysis
* Dynamic navigation and UI/UX enhancements
* Image-based slicers and field parameters

---

# 🛠️ Methodology & Execution

## 1. Dynamic Data Extraction & Transformation

* Imported data using the **Folder Import** method in Power Query.
* Created a dynamic folder path parameter.
* Enabled seamless dashboard migration across devices without breaking data connections.

## 2. Advanced Data Modeling

* Removed Power BI auto-generated relationships.

* Built a custom star schema model.

* Connected Fact Tables:

  * Sales
  * Inventory
  * Shipment
  * Production

* Connected Dimension Tables:

  * Product
  * Date
  * Customer
  * Supplier

* Used strict one-to-many relationships.

* Avoided bidirectional filtering to improve performance.

## 3. DAX Measure Development

Created a dedicated Measures Table and developed KPIs including:

### Financial Metrics

* Total Revenue
* Total Profit
* Profit Margin %

### Inventory Metrics

* Inventory Value
* Inventory Turnover Rate
* Days of Inventory
* Reorder Point

### Supply Chain Metrics

* Perfect Order %
* Defect Tracking
* Supply Chain Efficiency KPIs

### Time Intelligence

* Year-over-Year Revenue Growth
* `SAMEPERIODLASTYEAR()` implementation

## 4. UI/UX & Dashboard Storytelling

* Applied a custom JSON theme.
* Created a centralized Home Page.
* Built navigation buttons between report pages.
* Implemented Dynamic Field Parameters.
* Developed Image-Based Product Slicers.
* Maintained a clean and minimal dashboard design.

---

# 💡 Business Recommendations

## Supplier Optimization

* BOE Technology demonstrated the highest Total Unit Cost.
* Renegotiate supplier contracts.
* Shift procurement volume toward suppliers with stronger quality scores.

## Inventory Management

* Products approaching reorder points should be replenished immediately.
* Reduce excess inventory for slow-moving products.
* Improve overall Inventory Turnover Rate.

## Logistics Efficiency

Major shipment delays were caused by:

* Courier Capacity Issues
* Documentation Issues

Recommended actions:

* Secure guaranteed shipping capacity.
* Improve documentation processes and compliance checks.

## Customer & Channel Strategy

Top-performing channels:

* Amazon
* Retailers

Recommendations:

* Increase marketing investment in high-performing channels.
* Investigate underperformance of direct and online channels.

---

# 📈 Forecasting & Predictions

## Q4 Seasonal Demand Surge

Historical trends indicate significant growth during:

* October
* December

Recommended preparation:

* Increase warehouse staffing.
* Secure additional logistics capacity before Q4.

## Defect Rates vs. Production Volume

Observations:

* Highest defect rates occur during peak production months.
* Production growth may increase defects unless quality controls improve.

Recommendations:

* Strengthen QA procedures.
* Increase production monitoring during peak seasons.

---

# 🗣️ Key Takeaways

## Data Modeling is the Foundation

Understanding:

* Fact Tables
* Dimension Tables
* Relationship Management

is critical for scalable Power BI solutions and technical interviews.

## Keep Dashboards Minimal

Principles followed:

* Reduce visual clutter.
* Group information logically.
* Guide users through a clear data story.

## Focus on End Users

Implemented features specifically to improve usability:

* Dynamic path variables
* Navigation buttons
* Field parameters
* Interactive slicers

The primary objective was to make the solution both developer-friendly and business-user-friendly.
