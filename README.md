# mp-family-staff-expenses
A dataset of British MPs that employ a family member in their staff (or in a lobbying institution), coupled with the total staffing cost for that particular year

The staffing cost was scraped from the [**Independent Parliamentary Standards Authority**](http://www.theipsa.org.uk/mp-costs/your-mp/) using [**BeautifulSoup**](https://www.crummy.com/software/BeautifulSoup/) whereas the family members employed were taken from [**TheyWorkForYou**](https://www.theyworkforyou.com/regmem/?d=2016-03-21#11804) using regular expressions. The two tables were merged using the VLOOKUP function on Excel.
