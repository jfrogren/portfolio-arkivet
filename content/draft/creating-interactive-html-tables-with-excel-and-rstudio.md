---
title: "Creating Interactive HTML tables with Excel and RStudio"
date: 2021-01-27T09:45:04+01:00
draft: false
categories: ["Research methodology"]
---

In [the previous post](https://portfolio.arki.vet/post/classification-of-swedish-municipalities-for-study-ii/), I managed to create a table that was not just a simple Markdown table but one that was more dynamic or interactive. How I went about it, I will try to explain here. After a bit of googling, I realized that what I was asking for was [DataTables](https://web.archive.org/web/20210126183410/https://datatables.net/). But since I am curious about R and RStudio, I wanted to try to create a corresponding table in this way and not by using JavaScript or Custom Style Sheets (CSS) as the page indicates. However, I am a beginner when it comes to both R and RStudio, and especially when it comes to how to import data sets to work from, I do not understand much. Therefore, I thought it would be easiest to start the work of producing an interactive table by importing [the existing table in Excel format](https://web.archive.org/web/20210127090537/https://skr.se/download/18.125bed0a16eaec0acf39c42e/1575299317042/%C3%96versiktstabell%20och%20lista_Kommungruppsindelning%202017%20reviderad.xlsx). (The current table is available by clicking "Översiktstabell och lista på indelning 2017 (Excel, nytt fönster)" on [this page](https://web.archive.org/web/20201112001545/https://skr.se/tjanster/kommunerochregioner/faktakommunerochregioner/kommungruppsindelning.2051.html).)

[Here](https://web.archive.org/web/20201125091045/https://support.rstudio.com/hc/en-us/articles/218611977-Importing-Data-with-RStudio) it is described how Excel tables are imported into RStudio. This is done by selecting `Import Dataset` in the File menu, and then scrolling to the Excel sheet you want to import. When this is done, the code in RStudio looks like this: 

````
> library(readxl)
> O_versiktstabell_och_lista_Kommungruppsindelning_2017_reviderad <- read_excel("~/Documents/phd/thesis/artikel2/Översiktstabell och lista_Kommungruppsindelning 2017 reviderad.xlsx", 
+     sheet = "Lista Kommungruppsind 2017")
> View(O_versiktstabell_och_lista_Kommungruppsindelning_2017_reviderad)

````
To create what looks like DataTables, an R package called [DT](https://web.archive.org/web/20210127092246/https://rstudio.github.io/DT/) is needed. To achieve the table we are looking for, write the following code in RStudio in direct connection to the previous code: 

````
> library(DT)
> datatable(O_versiktstabell_och_lista_Kommungruppsindelning_2017_reviderad)

````

To then export this table, select `Export` followed by `Save as Web Page` in the menu just above the window where the table is visible. 

Done.

P.S. There are also ways of making these tables [downloadable](https://web.archive.org/web/20201022182632/https://martinctc.github.io/blog/vignette-downloadable-tables-in-rmarkdown-with-the-dt-package/). However, I don't see a need for that at the moment. 
