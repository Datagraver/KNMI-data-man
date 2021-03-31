# KNMI-data-man
Manipulated KNMI datasets for further use, like number of records, or summaries.

Still work in progress.

Here we place CSV's (with semi colon as seperator) with summaries from KNMI data.

KNMI_records_som_jaar.csv contains the number of records set for daily records (min, max for tg, tn and tx for a given day).
KNMI_huidige_extremen.csv contains the current tg, tn, tx extremes for a given day in the year, together with the year the current extreme is set.
KNMI_eerstedag_warmzomerstropischheet.csv contains the first day (daynumber) in a year a warm,zomers,tropisch day happens.
KNMI_tellers_warm_en_vorst.csv contains counters per year for:
warm days: > 20
zomer days: >25
tropische days: >30
heet days: >35
extreem heet days: > 40
based on max. temp.
and
lichte vorst days: <0
matige vorst days: <-5
strenge vorst days: <-10
zeer strenge vorst days: <-15
based on min. temp. 
Non overlapping (so "warm" only counts days between 20 and 24,9 degrees)


All data is from KNMI and starts in 1901.
https://www.knmi.nl/nederland-nu/klimatologie/daggegevens

Data will be updated once a day at 09:30 UTC.

All temperatures are in tenths of degrees Celcius
