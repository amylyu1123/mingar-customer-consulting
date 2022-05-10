This is the final group project from the U of T course *STA303H1: Methods of Data Analysis II*, which is a consulting project about analyzing customer persona and factors that affect sleep tracking performance for Mingar's fitness tracking wearable devices using *R*. 

**Details of this project can be found using the link https://sta303-bolton.github.io/sta303-w22-final-project/outsiders.html**

## Introduction

The client is the company, *Mingar*, which is a company (not a real company) that has developed products aimed at outdoor recreation over these years. Specifically, Mingar would like to expand product offerings about high-end fitness tracking wearable devices to grow with the market of wearables and gain market share. 

In order to achieve that and take into consideration their main competitor company, they have added new product lines, “Active” and “Advance” lines, with a more approachable price point. This leads to two research questions they are interested with:

- The **market team** wants the customers' and buyers' information to inform a strategy in the Canadian market. More importantly, they want to know if these two new lines have attracted customers outside of their traditionally high-income base. 
- The **social media team** has tracked a trend in complaints that their devices are performing poorly for users with darker skin, particularly with respect to sleep scores.

Our group created a consulting company called *Mega Consulting Company* for the purposes of this project and completed a pseudo-NDA. We investigated the above two research questions using appropriate statistical models (i.e. the Generalized Linear Mixed Model (**GLMM**)) and conducted data analysis using *R*. In the end, we demonstrated the result as a formal report.


**Details of the client's background and the research questions can be found using the link https://sta303-bolton.github.io/sta303-w22-final-project/emails.html**

## Data

The client has provided client datasets about their customers’ and devices’ information. Besides, we have census datasets (i.e. industry-standard data for wearable fitness trackers in the Candian market, household median income data, postal code conversion file) acquired by web scraping, using API, or downloaded from the U of T library. 

**Details of data can be found using the link https://sta303-bolton.github.io/sta303-w22-final-project/hints.html**

## Files Description

- **data-prep.Rmd** is the RMarkdown file that contains the data cleaning process and outputs the cleaned datasets to the **data** folder.
- **data** contains Rds files that are cleaned datasets that would be used directly when conducting data analysis.
- **sta303-final-project.Rmd** contains the main analysis, R codes and final report. 
- **sta303-final-project.pdf** is the pdf version of the final formal report knitted by **sta303-final-project.Rmd**.



