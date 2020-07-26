# Average-length-of-stay-in-hospitals

Introduction to problem:
How does an individual choose what hospital to go to if they have a condition which requires the individual to be admitted in for care? The natural answer comes down to how efficient a hospital is. One such measure of efficiency is Average Length of stay.
Average Length of stay: The average length of stay in hospitals (ALOS) is often used as an indicator of efficiency. All other things being equal, a shorter stay will reduce the cost per discharge and shift care from inpatient to less expensive post acute settings. The ALOS refers to the average number of days that patients spend in hospital. It is generally measured by dividing the total number of days stayed by all inpatients during a year by the number of admissions or discharges. Day cases are excluded. The indicator is presented both for all acute care cases and for childbirth without complications.

Problem Statement:
The aim of the investigation is to understand if there is any statistically significant difference in the average length of stay (ALOS) between large and medium hospitals which might make patients choose one over the other.
There are over 6000 data entries for Medium and Large Hospitals, it is intended to simplify the data analysis by grouping and visualizing the spread of ALOS in these groups.

Data:
The data has been downloaded from the website of Australian Institute of Health and Welfare.
The Data has been collected over 6 years 2011 2017 for hospitals in Australia with defined peer groups based on size (like Medium and Large) and major practice in Hospital (like Children s Hospital).
The metrics like number of stays, number of overnight stays, and total overnight patient bed days go on to make the metric in question Average Length of stay.

Nature of Analysis:
Various statistical techniques have been used to come to conclusion, you can look up the internet to understand the various concepts implemented in the notebook.
Two tailed t-test, Lavene test etc are the tests that have been done.

Conclusions:
The most significant result from our Analysis is that the Larger hospitals have greater ALOS than Medium Hospitals.
The higher ALOS directly points at lesser efficiency of Larger Hospitals.
The data was highly skewed in Large hospitals towards higher ALOS, also a greater number of outliers were present. This could mean a bunch of hospitals affecting the efficiency of the Peer group.
There is a fair possibility of removing the outlier and rechecking the difference in means to find them equal.
This result is food for thought for all those who have to be admitted for any sort of care in future, the better choice seems to be facing towards Medium hospitals rather than Large.

References
https://www.aihw.gov.au/reports-data/myhospitals/sectors/admitted-patients
https://data.oecd.org/healthcare/length-of-hospital-stay.htm
