# Global E-Commerce Executive Intelligence

## Dataset

Source:
UCI Machine Learning Repository – Online Retail II (2009–2011)

Dataset Size:
1,067,371 rows × 8 columns

### Schema

| Column | Description |
|----------|------------|
| Invoice | Invoice number |
| StockCode | Product code |
| Description | Product description |
| Quantity | Quantity purchased |
| InvoiceDate | Date and time of transaction |
| Price | Unit price |
| Customer ID | Unique customer identifier |
| Country | Customer country |

### Data Quality Challenges

- Missing Customer IDs
- Negative quantities representing returns
- Cancelled invoices beginning with "C"
- Inconsistent product descriptions


### Outline Cleaning Steps

Based on the initial data profiling, the following cleaning steps were planned.

- Remove duplicate records
- Handle missing values in important columns such as CustomerID and Description
- Convert InvoiceDate to datetime format
- Verify and correct datatypes for numerical columns
- Remove or investigate records with negative Quantity and UnitPrice values
- Standardize text fields by removing extra spaces and ensuring consistent capitalisation
- Check for invalid or inconsistent values in categorical columns such as Country
- Remove unnecessary columns that are not required for analysis.
