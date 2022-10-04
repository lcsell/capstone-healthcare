# Capstone Healthcare


### Objective
Health insurance is a type of insurance that covers a portion of the cost of medical expenses. There is a portion of the population that is uninsured in the United States; understanding the factors behind lacking health insurance or sufficient access to healthcare could illuminate the way to improve health insurance coverage in the country and identify which American communities that are most in need of increased healthcare coverage and access. For the purpose of this work, those with *sufficient access to healthcare* include people who do not delay or avoid seeking healthcare services due to cost. *Uninsured* includes those who do not have health insurance for any reason.

We are interested in understanding the factors that lead to a lack of health insurance and lacking health insurance or sufficient access to healthcare nationwide and in the counties in Minnesota in 2019. We are looking into race and ethnicity, gender, age, income, immigration status, educational attainment, and location to see how these play a role in someone’s insurance status. 




### Exploratory Questions
  * How do unisurance rates vary among various demographics such as race, age, sex, population, income, educational attainment level?
  * How does access to health care vary at a national level and by county?
  * How does access to health care vary among Minnesota counties?
  * Does the rate of uninsurance vary for individuals based on the number of hospitals in their county?
  * Can we predict which areas will have more or less coverage based on demographics, income, hospital count or other factors?
  * For those who are covered, is their coverage sufficient for their health needs?



### Initial datasets:
  * Census SAHIE 
      * [2019 Small Area Health Insurance Estimates (SAHIE) using the American Community Survey (ACS) ](https://www.census.gov/data/datasets/time-series/demo/sahie/estimates-acs.html)
  * BRFSS: Healthcare Access/Coverage
      * [BRFSS: Table of Health Care Access/Coverage | Chronic Disease and Health Promotion Data & Indicators (cdc.gov)](https://chronicdata.cdc.gov/Behavioral-Risk-Factors/BRFSS-Table-of-Health-Care-Access-Coverage/f7a2-7inb)
  * Healthcare estimates by demographics & population (Census)
      * [S2701: SELECTED CHARACTERISTICS OF... - Census Bureau Table](https://data.census.gov/cedsci/table?q=health%20insurance&g=0400000US27,27%240500000&tid=ACSST1Y2021.S2701&moe=false)
      * Private health insurance: [S2703: PRIVATE HEALTH INSURANCE... - Census Bureau Table](https://data.census.gov/cedsci/table?q=health%20insurance&g=0400000US27,27%240500000&tid=ACSST1Y2021.S2703)
      * Public health insurance: [S2704: PUBLIC HEALTH INSURANCE... - Census Bureau Table](https://data.census.gov/cedsci/table?q=health%20insurance&g=0400000US27,27%240500000&tid=ACSST1Y2021.S2704)
   * [Hopsital count by county in Minnesota for 2019](https://data.census.gov/cedsci/table?q=hospital%20cb&g=0400000US27,27%240500000)
   * [Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Prevalence Data (Subset for 2019)](https://chronicdata.cdc.gov/Behavioral-Risk-Factors/Behavioral-Risk-Factors-Selected-Metropolitan-Area/j32a-sa6u/data)
   * [National Health Interview Survey](https://www.cdc.gov/nchs/nhis/index.htm)
   * [Population estimates and demographics by county for Minnesota for 2019](https://data.census.gov/cedsci/table?q=county%20population&g=0400000US27,27%240500000&tid=ACSDP1Y2021.DP05&moe=false)



### Entity Relationship Diagram:
![CapstoneERD](https://user-images.githubusercontent.com/110693932/192833067-60242816-bda7-4ec2-93db-b53e26b6bf7e.png)



### Data Platform Diagram:
![Data_Platform_Diagram](https://user-images.githubusercontent.com/110693932/192818805-a0e8ec38-2a1c-4a01-8849-2e7805281b0c.png)


### Library versions for other Jupyter notebooks
* Numpy version: 1.20.3
* Pandas version: 1.3.4
* Pyspark version: 3.3.0
* Requests version: 2.28.1
* Scipy version: 1.7.1
* Sklearn version: 0.24.2
* Sodapy version: 2.2.0
* Statsmodels version: 0.12.2


### Library versions for running ML Model
* Python version: 3.10.6
* Matplotlib version:3.6.0
* Numpy version: 1.23.3
* Pandas version: 1.5.0
* Pymssql version: 2.2.5
* Seaborn version: 0.12.0
* Sklearn version: 1.1.2