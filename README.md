# OT-centralreach-timesheets
calculates OT for timesheet exports from CentralReach

This program runs on Jupyter Notebook to get a list of providers that have Overtime (time that exceeds 8 hours per work day) with their total Overtime and calculate the premium on top of regular pay for the Overtime based on their rates.

Input file:
Raw export csv file from the "Timesheets" view under "Billing" in CentralReach

Output file:
Csv file with a list of all Overtime providers, their total overtime, and the total premium pay of the overtime

---
DISCLAIMER: This program does not account for cases when providers work over 12 hours per day (Double time) or if a provider accumulates Overtime by working a consecutive 7 days per week.
