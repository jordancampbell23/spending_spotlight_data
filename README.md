# Spending Spotlight Paper
 Data validation for Spending Spotlight 2.0 paper

## Instructions

### BLS - CPI
- FY annual average checked for 2020, 2019, 2018 all match (05/10/23) https://fred.stlouisfed.org/series/CPIAUCSL

### NCES - Digest of Education Statistics:
 - Teacher Salary: 
   - 2020: https://nces.ed.gov/programs/digest/d21/tables/dt21_211.60.asp
   - 2002: https://nces.ed.gov/programs/digest/d04/tables/dt04_078.asp
 - Teachers / Non-Teachers:
   - 2020: https://nces.ed.gov/programs/digest/d21/tables/dt21_213.40.asp
   - 2002: https://nces.ed.gov/programs/digest/d05/tables/dt05_081.asp
 - Complete Staffing (seem to be multiple sources for this): 
   - 2020: https://nces.ed.gov/programs/digest/d21/tables/dt21_213.20.asp
   - 2002: https://nces.ed.gov/programs/digest/d04/tables/dt04_081.asp
### NCES
#### NAEP General
Click the link (https://www.nationsreportcard.gov/data_tools.aspx) and go to Data Explorer. The selections should follow logically (4th/8th grade reading/math for the years between 2003 and 2019). For 12th grade reading the year time range is between 2002 and 2019—and the math time range is between 2005 and 2019.

#### Long-Term NAEP
Downloadable data can be found at the bottom of this page: https://www.nationsreportcard.gov/ltt/mathematics/student-group-scores/?age=9.
 



# Methodology

## Data Sources
 - NAEP Data
 - NCES 
 - U.S. Census Bureau
 - Bureau of Labor Statistics

## NAEP Data

The National Assessment of Educational Progress (NAEP) is a congressionally mandated assessment 
of what students know and can do in various subjects. NAEP is the only nationally representative 
and continuing assessment of what America’s students know and can do in various subject areas. 
NAEP is administered to students in grades 4, 8, and 12 in mathematics, reading, science, writing, 
the arts, civics, economics, geography, U.S. history, and world history. 

We focused on math and reading scores for grades 4, 8, and 12. Twelveth grade scores are only available
at the national level. NAEP is not administered every year, so we included scores from 2003 to 2019 to 
match the years of our other data sources. The years included for 4th and 8th grade math and reading are 2003, 
2005, 2007, 2009, 2011, 2013, 2015, 2017, and 2019. 

The NAEP data is available: https://nces.ed.gov/nationsreportcard/naepdata/

## NCES

The National Center for Education Statistics (NCES) is the primary federal entity for collecting and 
analyzing data related to education. We used the NCES Digest of Education Statistics to get data on the
number of teachers and non-teachers, general staffing, and teacher salaries.

The NCES Digest of Education Statistics is available: https://nces.ed.gov/programs/digest/

## U.S. Census Bureau

The U.S. Census Bureau produces the Annual Survey of School System Finances. These data include revenue, 
expenditure, and enrollment data by state. The data used from this report include, revenue 
(federal, state, and local), instructional expenditures, support services expenditures, salary and benefit 
expenditures, capital outlays, and debt for the fiscal years 2002 to 2020.

The U.S. Census Bureau is available: https://www.census.gov/programs-surveys/school-finances.html

## Bureau of Labor Statistics

The Bureau of Labor Statistics (BLS) produces the Consumer Price Index for All Urban Consumers: All Items (CPIAUCSL).
This commonly used price defaltor is frequently just referred to as CPI. We used a monthly average over the fiscal year (July to June)
to get an average CPI for each school year. BLS will frequently release revisions to the CPI, the CPI values used in this paper
were pulled from CPIAUCSL on 03/15/2023.
