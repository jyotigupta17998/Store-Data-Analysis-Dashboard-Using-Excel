# Data Dictionary — Vrinda Store Raw Dataset

This document describes each column in `Vrinda_Store_Raw_Data.xlsx`.

- **Order ID**: Unique order identifier (string)
- **Cust ID**: Customer identifier (numeric/string)
- **Gender**: Customer gender (Men / Women)
- **Age**: Customer age (integer)
- **Age_grp**: Age group (Teenager / Adult / Senior)
- **Date**: Order date (DD-MM-YYYY)
- **Month**: Month name (Jan, Feb...)
- **Status**: Order status (Delivered, Returned, Cancelled, Refunded)
- **Channel**: Sales channel (Amazon, Flipkart, Myntra, Ajio, Meesho, Others)
- **Category**: Product category (e.g., Blouse, Kurta, Bottom)
- **Amount**: Order amount (numeric)
- **Other fields**: [Add any custom columns you used]

Notes:
- Missing values replaced with standard labels (e.g., 'Unknown')
- Dates normalized to ISO format where required
