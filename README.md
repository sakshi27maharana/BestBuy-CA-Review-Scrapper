# BestBuy-CA-Review-Scrapper

## Objective 1:
Python script to scrape product reviews from an e-commerce website - www.bestbuy.ca/en-ca. The script should handle multiple filters, paginate through review pages, and extract key review details. The code should only extract the data available for public view and should not violate any website policy.

This task is designed to evaluate your data analytics and value addition approach to solve
customer problems. The response of this assignment will be evaluated on –
• Understanding of data and tools used to perform the analysis
• Value generation via potential insights found during analysis
• Documentation/presentation to stakeholders

### Guidelines -

  1. Setup - Choose a Web Scraping Library: Use a Python web scraping library such as
Selenium, Beautiful Soup, or similar tools.
Apply Filters and Load Pages: Implement functionality to apply multiple filters and load all pages to maximize the number of reviews mined.
    
  2. Data Scraping- Extract Required Details having below fields, but not limited to:

     a. Primary Key
     
      b. Title
     
      c. Review Text
     
      d. Date (formatted as YYYY-MM-DD)
     
      e. Rating (out of 5)
     
      f. Source
     
      g. Reviewer Name

  3. Additional comments on scraping
     
      a. Pagination and Filters - Handle Pagination by clicking the "Show More" buttons
      to access all available reviews.
     
      b. Use filters such as "Most Helpful," "Newest," "Highest Rating," "Lowest Rating,"
      and "Most Relevant" to refine the review extraction process.
     
  4. Sentiment Analysis – Provide a code example that demonstrates the complete
process loading the review text, preprocessing it if necessary, applying a suitable
model or technique for sentiment analysis, and categorizing the results.

  5. Suggested solution for scraping challenges

      a. Suggest ways to handle anti-scraping blockers e.g. rotating proxies, CAPTCHA bypass, or retry mechanisms, IP blocking.

  6. Business Context

      a. Provide a summary of insights, such as top drivers of customer satisfaction and dissatisfaction, with recommendations for improvement.

## Objective 2:

Perform comprehensive EDA, text mining, and actionable insight generation
using the provided dataset.

### Guidelines –

  1. Exploratory Data Analysis (Using python)
     
      a. To understand data types, volume and characteristic per column. Identify and solve for missing values, duplicated and other inconsistencies found.

      b. Identify critical columns that looks insightful for stakeholders and provide a summary of key statistical analysis along with distribution/visualizations for critical columns identified.

  2. Text Mining (Using NLP/open source LLM based)
     
      a. Transform unstructured data into Structure format –
     
        i. To identify free text columns given in raw data.
     
        ii. Use text mining techniques to extract meaningful tags from the free text fields. (Refer to few examples of entities (but not limited to) given in excel file)
     
      b. Categories “type of issues” (e.g. component failure, electrical issue etc.) based upon observation/grouping of mined entities.
     
  3. Insights for stakeholders
     
      a. Identify patterns and trends, highlighting significant changes in event frequencies, e.g. most occurring failure reported
     
      b. Provide actionable recommendation for stakeholders to improve product quality and performance based upon your analysis.

      c. Apply clustering or topic modelling techniques to group failure modes or customer complaints into categories.

        i. identify potential root causes for recurring failures.

