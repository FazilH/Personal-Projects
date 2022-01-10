# Exploratory Data Analysis

# 

# Exploratory Data Analysis (EDA) is an analysis approach that identifies general patterns in the data. EDA is an important first step in any data analysis. Understanding how variables are related can help one design statistical analyses that yield meaningful results.

# 

# Dataset Used : [US Consumer Finance Complaints \| Kaggle](https://www.kaggle.com/kaggle/us-consumer-finance-complaints)

# Description:

# US consumer complaints on financial products and company responses. Each week [the CFPB](http://www.consumerfinance.gov/data-research/consumer-complaints/) (Consumer Financial Protection Bureau) sends thousands of consumers’ complaints about financial products and services to companies for response. Those complaints are published here after the company responds or after 15 days, whichever comes first.

# 

| **Field Name**               | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Date received                |  The date the CFPB received the complaint. For example, “05/25/2013.”                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Product                      | The type of product the consumer identified in the complaint. For example, “Checking or savings account” or “Student loan.”                                                                                                                                                                                                                                                                                                                                                                                                 |
| Sub-product                  | The type of sub-product the consumer identified in the complaint. For example, “Checking account” or “Private student loan.”                                                                                                                                                                                                                                                                                                                                                                                                |
| Issue                        | The issue the consumer identified in the complaint. For example, “Managing an account” or “Struggling to repay your loan.”                                                                                                                                                                                                                                                                                                                                                                                                  |
| Sub-issue                    | The sub-issue the consumer identified in the complaint. For example, “Deposits and withdrawals” or “Problem lowering your monthly payments.”                                                                                                                                                                                                                                                                                                                                                                                |
| Consumer complaint narrative | Consumer complaint narrative is the consumer-submitted description of “what happened” from the complaint. Consumers must opt-in to share their narrative. We will not publish the narrative unless the consumer consents, and consumers can opt-out at any time. The CFPB takes reasonable steps to scrub personal information from each complaint that could be used to identify the consumer.                                                                                                                             |
| Company public response      | The company’s optional, public-facing response to a consumer’s complaint. Companies can choose to select a response from a pre-set list of options that will be posted on the public database. For example, “Company believes complaint is the result of an isolated error.”                                                                                                                                                                                                                                                |
| Company                      | The complaint is about this company. For example, “ABC Bank.”                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| State                        | The state of the mailing address provided by the consumer.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ZIP code                     | The mailing ZIP code provided by the consumer. This field may: i) include the first five digits of a ZIP code; ii) include the first three digits of a ZIP code (if the consumer consented to publication of their complaint narrative); or iii) be blank (if ZIP codes have been submitted with non-numeric values, if there are less than 20,000 people in a given ZIP code, or if the complaint has an address outside of the United States).                                                                            |
| **Field Name**               | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Tags                         | Data that supports easier searching and sorting of complaints submitted by or on behalf of consumers. For example, complaints where the submitter reports the age of the consumer as 62 years or older are tagged “Older American.” Complaints submitted by or on behalf of a servicemember or the spouse or dependent of a servicemember are tagged “Servicemember.” Servicemember includes anyone who is active duty, National Guard, or Reservist, as well as anyone who previously served and is a veteran or retiree.  |
| Consumer consent provided?   | Identifies whether the consumer opted in to publish their complaint narrative. We do not publish the narrative unless the consumer consents, and consumers can opt-out at any time.                                                                                                                                                                                                                                                                                                                                         |
| Submitted via                | How the complaint was submitted to the CFPB. For example, “Web” or “Phone.”                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Date sent to company         | The date the CFPB sent the complaint to the company.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Company response to consumer | This is how the company responded. For example, “Closed with explanation.”                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Timely response?             | Whether the company gave a timely response. For example, “Yes” or “No.”                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Consumer disputed?           | Whether the consumer disputed the company’s response.                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Complaint ID                 | The unique identification number for a complaint.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

**Steps performed:**

1.  Checked the shape of data, different variable present in the data and number
    of unique values each in variable.

2.  Checked the missing values, duplicate values and plotted the percentage of
    missing values for each variable.

3.  Displayed the different product complaints was made about.

4.  Plotted the frequency plot for the different datatypes.

5.  Checked for the minimum and maximum date to find out the period between
    which the data is recorded.

6.  Trend chart for complaints at monthly granularity level.  
    Used only the data for year 2012,2013,2014 & 2015, data for year 2011 and
    2016 is not used because 2011 has only one month of data and 2016 has only
    four month of data.

7.  Trend chart for complaints at yearly granularity level.

8.  Chart for product-wise complaints count.

9.  Stacked bar chart of top 10 states with most complaints showing whether
    consumer disputed or not.

10. Stacked bar chart of top 10 company with most complaints showing whether the
    response provided to the consumer is on-time or not.

11. Count plot of different responses provided to the consumers by the
    companies.

12. Chart for avg no. of days taken for the complaint to reach to the company
    depending upon the mode of submission.
