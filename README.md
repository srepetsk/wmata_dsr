# wmata_dsr
This repository is meant to hold processed WMATA Daily Service Report information from the agency. New data is available from (the WMATA website)[http://www.wmata.com/rail/service_reports/viewPage_update.cfm].A

# Warnings
There is data missing:
- February 16th, 2011 - April 29th, 2012 is gone
- Data in this document starts on January 1st, 2009

## wmata_dsr_raw.csv:
- Month
- Day
- Year
- Time of day
- Line affected (sometimes this is All if it is system-wide)
- Reason for delay
- Delay (minutes)
- Details (raw delay data from WMATA)

# Warranty Clause
The raw dataset this repository is based on is available unformatted and free of charge by WMATA. There are no guarantees or warranties expressed by this processed dataset, and there are likely to be errors. Commits or notes about missing/errant data are greatly appreciated!
