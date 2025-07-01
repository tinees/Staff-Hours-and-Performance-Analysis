Staff Hours Analysis (Excel)

This project demonstrates a simple staff-hours tracking system built in **Excel** for analyzing workforce distribution across multiple weeks.

📊 Features

- Tracks hours worked by each staff member over multiple weekly periods
- Summarizes total hours per person
- Includes meeting time tracking and shift distributions
- Built-in Excel formulas and structure for manual or semi-automated updates

🔧 Excel Logic & Formulas Used
This workbook uses custom formulas to calculate hours, payroll readiness, and performance bonuses. Below are some of the key formulas:
- `=COUNT(B4:H4)`  
  → Counts days worked in the first week.

- `=SUM(Q4:R4)`  
  → Calculates total days worked across two weeks (for fortnightly payroll).

- `=IF(B4 > 4.5, (B4 * 60 - 30) / 60, B4)`  
  → Adjusts hours if a shift exceeds 4.5 hours (subtracts a 30-minute break).

- `=SUM(B10:H10)`  
  → Sums total hours worked in the first week.

- `=Q10 + R10`  
  → Totals hours over two weeks for pay calculation.

- `=SUM(B16:H16)`  
  → Sums total sales for the first week.

- `=Q16 / Q10`  
  → Calculates hourly sales productivity index.

- `=IF(R16 > 90, R16 * 0.03, "")`  
  → Bonus calculation: if sales/hour index exceeds $90, apply a 3% bonus.


🧠 Skills Demonstrated

- Excel formulas (`SUM`, totals)
- Spreadsheet structuring and layout for analysis
- Manual data analysis across time periods
- Data cleaning and formatting
- Anonymized for portfolio use

🔍 Sample Use Cases

- Internal HR or team planning
- Performance and capacity tracking
- Scheduling support for retail or shift-based work

📁 File

- `Staff_Hours_Anonymized.xlsx` – mock version of a real-world project (no sensitive data)

🚫 Notes

- All names and data in this version are anonymized.
- Based on a real internal project, recreated with generic values for demonstration.

