# Week 2 Task: Data Cleaning and Data Modeling

## Data Cleaning
- Removed duplicate records from tables to avoid redundancy.
- Addressed missing values by imputing or assigning placeholder values where appropriate.
- Standardized data formats for consistency (e.g., date formats, text casing, decimal precision).
- Validated key fields (e.g., `SKU`, `Supplier Name`, `Product Type`) to ensure data integrity.
- Corrected outliers in numerical fields (e.g., defect rates) and removed irrelevant data.

## Data Modeling
- Established relationships between tables:
  - **Inventory Table ↔ Supply Chain Table** via `SKU`.
  - **Supply Chain Table ↔ Supplier Table** via `Supplier Name`.
  - **Manufacturing Table ↔ Inventory Table** via `SKU`.
- Defined primary and foreign keys for linking tables.
- Normalized data to eliminate redundancy and ensure logical organization.
- Created and optimized relationships in Power BI with appropriate cardinality (one-to-many, many-to-one).

This process ensures a clean and structured dataset for accurate analysis and visualization in Power BI.

