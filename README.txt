** Call Center Report for Sea Mar Community Health Centers **

All phone numbers and names have been anonymized.

The project processes lines of raw phone call data from CISCO to retieve key metrics. No VBA code was used to make sure that the sheet could be used by anyone in the organization.

This report became the primary call report used by Front Office Supervisors, Clinic Managers, and VPs throughout the organization, and was submitted with all new hires as part of the FTE justification process.
A tutorial on use was included with the report, as well as an email link so that I could be easily reached to provide support for the report.

This example contains over 30,000 lines of data, and organizes them into a report that tracks the following:
* Reception FTE needed to cover calls.
* Incoming call volume by weekday and time of day.
* Abandoned calls by weekday and time of day.
* Call queue wait-time by weekday, time of day, as well as minimum and maximum values.
* Employee stats such as calls taken per day, average handling time, and deviation from the average.
* Total calls within the report period, answer percentage, total unique callers, etc.


Key Formula used:
* Sumproduct() - Used as a sieve to organzie data around call type (answered / abandoned), time of day, weekday, and add up the call handling time.
* Index() Match() paired to organize data on the reports.
* Countifs and String processing formula to create helper columns and make the reports easier to read.


