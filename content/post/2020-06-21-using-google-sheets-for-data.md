---
title: Using Google Sheets for data
author: Ian D. Gow
date: '2020-06-21'
slug: using-google-sheets-for-data
categories: []
tags: []
---

[Karl Broman](https://kbroman.org/) and [Kara Woo](https://karawoo.com/) have a excellent article in *The American Statistician* 
entitled "[Data Organization in Spreadsheets](https://doi.org/10.1080/00031305.2017.1375989)".
Broman and Woo suggest that, despite well-understood problems, "spreadsheets have continued to play a significant role in researchers' workflows, and it is clear that they are a valuable tool that researchers are unlikely to abandon completely."
Broman and Woo make a number of recommendations that I broadly agree with.
However, I argue that some of their recommendations are based on a the kind of the data-collection efforts they have in mind and require modification in settings I encou

### Data collection

The examples provided by Broman and Woo appear to relate to things such as collecting temperature readings or glucose levels, perhaps in the field or the lab. 
These are essentially *primary* data collection and I think that recommendations such as  
"Create a Data Dictionary" and Make Backups" make a lot of sense in such settings.

But I have used spreadsheets in very different settings from these.
My primary data are generally from commercial or academic databases containing stock prices, 
financial statement information, or other information on firms, such as details about directors. Here are examples of data-collection efforts where I have used spreadsheets:

- Firm identifier links (e.g., linking CUSIPs to CIKs).
- Directorships held by directors of US firms
- Ethnicity of directors of US firms
- Audit fees for Australian firms
- Gender of individual directors of Australian firms

There are some features of these efforts that distingush them from the examples provided by Broman and Woo.
First, the primary data source is the internet or other preexisting data sources.

Second, the data collection efforts were supplementary.
For example, 

## Recommendations of Broman and Woo

1. Be Consistent
2. Choose Good Names for Things
3. Write Dates as `YYYY-MM-DD`
4. No Empty Cells
5. Put Just One Thing in a Cell
6. Make it a Rectangle
7. Create a Data Dictionary
8. No Calculations in the Raw Data Files
9. Do Not Use Font Color or Highlighting as Data
10. Make Backups
11. Use Data Validation to Avoid Errors
12. Save the Data in Plain Text Files
