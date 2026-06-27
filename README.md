# Who Applied for the H-1B Lottery?

H-1B is a U.S. visa program that allows companies to hire skilled foreign workers in specialized occupations. Every year, hundreds of thousands of people register for the H-1B lottery, making it an important topic for immigration and the technology industry. This project uses H-1B registration data to explore two simple questions: Where do applicants come from, and which employers submit the most registrations? Understanding these patterns helps provide a clearer picture of who participates in the H-1B lottery.

## Introduction to the dataset

This project uses H-1B lottery registration data shared by Bloomberg News. Bloomberg obtained the data through a Freedom of Information Act (FOIA) request from the US government. The original dataset includes H-1B registration records from FY2021 to FY2024. For this project, I analyzed a random sample of 50,000 records from the FY2021 dataset. The original FY2021 dataset contains 269,424 records, so I selected a random sample to keep the analysis manageable while using Google Sheets. Although the data come from an official government source, there are still some limitations. Some companies appear under different names, and this project only looks at one year of data. Because I used a sample instead of the full dataset, the results may not exactly match the complete dataset.

Link for: [Original data source](https://github.com/BloombergGraphics/2024-h1b-immigration-data)

Link for: [Google sheets](https://docs.google.com/spreadsheets/d/1ZTmgfvTfUerljE3Qly185A0pYRSU0UoyxTDNRjJAkwE/edit?usp=sharing)  

## Result 1: Where did applicants come from?

### Top 10 Nationalisties of H-1B Applicats (2021)

![alt text](image.jpg)

This bar chart shows that applicants from India make up the largest share of the sample, followed by China. Applicants from other countries appear much less frequently. This suggests that H-1B registrations were heavily concentrated among a small number of nationalities in FY2021. It also shows that applicants from India made up a much larger share than any other country in the sample.

## Result 2:  Which employers submitted the most registrations?

### Top 10 Employers Submitting H-1B Registrations （2021)

![alt text](image.jpg)

This bar chart shows that several large technology and IT consulting companies submitted the highest numbers of H-1B registrations in the sample. Infosys, Amazon, Cognizant, and Tata Consultancy Services ranked among the largest employers. This suggests that H-1B registrations were concentrated among a relatively small group of large employers rather than being evenly distributed across companies.

## Ending summary

This project found that most H-1B registrations in the sample came from a small number of countries, especially India and China. It also showed that several large technology and IT consulting companies submitted the highest numbers of H-1B registrations. However, these results should be interpreted carefully. The data should not be used to stereotype people from any country or suggest that companies with many registrations did anything wrong. This project only shows patterns in the data and cannot explain the reasons behind them. To make this a more complete and ethical story, more reporting would be needed. For example, future research could compare data from different years, clean employer names to combine duplicate company records, and interview immigration experts or employers to better understand the results. However, this project is based on a random sample rather than the complete FY2021 dataset, the findings may not fully represent all H-1B registrations from that year.
