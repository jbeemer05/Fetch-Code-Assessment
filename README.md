# Fetch-Code-Assessment

Are there any data quality issues present?

Looking through the data and some descriptive statistics, there seems to be a good amount of missing data. In the Products file 92% of 'Category 4' is missing and ~26% rows are missing Brand and Manufacturer. In the Transactions file there are two rows per 'Receipt ID' with Final Quantity being on one and Final Sale being on the other. Final Quantity also has 'zero' and '1' as its values mixing data types. In the Users file 30% of Users do not have a Language specified. Barcode seems to be a float when it should be a string, and not all transactions have Barcodes, 11% missing.

Are there any fields that are challenging to understand?

In the Users file the Language column is not defined, but assuming English and Spanish. The Category columns in the Product file are not defined, but seem to be a categories that get more specific as you get to go from category 1 to category 4.
