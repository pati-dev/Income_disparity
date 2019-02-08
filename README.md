# Income_disparity

Data source:
https://www.gc.cuny.edu/Page-Elements/Academics-Research-Centers-Initiatives/Centers-and-Institutes/Stone-Center-on-Socio-Economic-Inequality/Core-Faculty,-Team,-and-Affiliated-LIS-Scholars/Branko-Milanovic/Datasets
WPID is the Lakner-Milanovic World Panel Income Distribution data set (Stata fileLMWPIDweb2.dta.)
Ventile(Stata fileventile2011forreleaseLCU.dta) contains more recent data (circa 2011.)

Metadata:

Potentially useful variables include in WPID:
•country:  country name
•contcod:  3-letter country code
•binyear:  the year for which incomes are estimated (1988 to 2008.) For technical reasons,use this rather than the year variable.
•group:  the income decile group the estimate is for, where a decile is 10% of the population. “1” means the 10% of individuals in the country with the lowest income, while “10” means the 10% of the individuals in the country with the highest income.
•RRinc:  the per capita income of that decile in that country, in 2005 US dollars.
•RRmean:  the mean per capita income of the whole country, in 2005 US dollars.

Some important variables in Ventile are:
•contcod:  3-letter country code
•ventile: the income ventile group the estimate is for, where a ventile is 5% of the population. “1” means the 5% of individuals in the country with the lowest income, while “20” means the 5% of the individuals in the country with the highest income.
•ventileincome:  the  per  capita  income  of  that  ventile  in  that  country.   Important:  This number is NOT adjusted for currency or inflation,  so it is not directly comparable to the incomes in the WPID data set (or to other countries in the Ventile data set.)
