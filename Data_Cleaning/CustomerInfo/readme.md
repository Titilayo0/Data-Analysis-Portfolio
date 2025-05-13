
#  CustomerInfo Dataset – Data Cleaning Process

The `CustomerInfo` dataset was cleaned and transformed in Power Query to improve its structure, readability, and suitability for analysis. Below is a breakdown of the steps taken:

##  1. Splitting Columns by Delimiters
- Full names originally stored in a single field were split into `First Name` and `Last Name` using a delimiter (likely space or uppercase transition).
- Address components may have been split to isolate street, city, or region details for further analysis.

##  2. Changing Data Types
- The `Age` column was converted to numeric.
- `Gender` was ensured to be of text type for consistency.
- Data types were validated and updated across the dataset to match their intended formats.

##  3. Removing Unnecessary Columns
- Redundant columns generated during the splitting process were removed to declutter the dataset.

##  4. Renaming Columns
- Columns were renamed for clarity and standardization, using readable formats like `Full Names`, `Address`, `Age`, and `Gender`.

##  5. Replacing Values
- Specific values (e.g., typos, inconsistent casing, or nulls) were likely corrected or replaced for uniformity.

##  6. Merging Columns
- `First Name` and `Last Name` were recombined into a new `Full Names` column to simplify the final output.

---

##  Final Result
The cleaned dataset contains:
- `Full Names` (merged from First and Last names)
- `Address`
- `Age` (as whole numbers)
- `Gender` (cleaned and categorized)

This structured data is now ready for use in further analysis.

