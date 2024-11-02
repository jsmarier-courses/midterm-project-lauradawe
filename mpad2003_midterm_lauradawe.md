**Nov 3, 2024**<br>
**MMPAD2003 - Introductory Data Storytelling**<br>
**Laura Dawe**<br>
**Presented to Jean-Sébastien Marier**<br>

# Midterm Project: Exploratory Data Analysis (EDA)



## Foreword

This project was to uncover insights, patterns, and trends with storytelling potential based on data taken from service calls to the City of Ottawa. The data was extracted from the City of Ottawa Open Data Portal and was a subset of data containing 28,539 entries covering the period between August 1 and September 1, 2024. The methodology used to clean the data was primarily linear using a vimo analysis, google sheets tools, and open refine. Key observations and takeaways include:xxxxxxxx
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)



## 1. Introduction

Putting into practice what has been learned in class, this project was to uncover insights, patterns, and trends with storytelling potential based on data taken from service calls to the City of Ottawa. The data was extracted from the City of Ottawa Open Data Portal and was a subset of data containing 28,539 entries covering the period between August 1 and September 1, 2024. The methodology used to clean the data was primarily linear using a vimo analysis to correct or remove invalid data; google sheets tools were applied to refine the data set down to its essential elements; open refine further summarised outputs for better identification. Analysis is based on quantitative methodology, using numerical data counts to quantify patterns. While there was some feedback between analysis and data cleaning, there was not a significant amount of iteration.

The datasets used in this analysis:
* [City of Ottawa's open data portal *"2024 Service Requests"*](https://open.ottawa.ca/documents/65fe42e2502d442b8a774fd3d954cac5/about)
* [Sub-dataset (2024-08-01 to 2024-09-01) from Jean-Sébastien Marier Github repo](https://raw.githubusercontent.com/jsmarier/course-datasets/refs/heads/main/ottawa-311-service-requests-august-2024.csv)

This report is composed of the following sections:
1. Getting Data
1. Understanding Data
    - VIMO analysis
    - Cleaning Data
    - Exploratory Data Analysis (EDA)
1. Potential Story
1. Conclusion
1. References

## 2. Getting Data

Google Sheets import function was used to open the downloaded .csv dataset file from Github.  The seperator was defined a ','.  See resulting file in Fig. 1.


![](Screenshot_RawDataImport.png)<br>
*Figure 1: Initial raw data import into Google Sheets.*

This also shows how to create an ordered list. Simply put `1.` before each item.

## 3. Understanding Data

### 3.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As Cairo (2016) argues, a data visualization should be truthful...

### 3.2. Cleaning Data


![](Screenshot_CleanedData.png)<br>
*Figure 2: Dataset after appling Google Sheets cleaning tools.*


**Here are examples of functions and lines of code put in grey boxes:**

1. If you name a function, put it between "angled" quotation marks like this: `IMPORTHTML`.
1. If you want to include the entire line of code, do the same thing, albeit with your entire code: `=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)`.
1. Alternatively, you can put your code in an independent box using the template below:

``` r
=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)
```

### 3.3. Exploratory Data Analysis (EDA)

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 4. Potential Story

Insert text here.

## 5. Conclusion

Insert text here.

## 6. References

Include a list of your references here. Please follow [APA guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
