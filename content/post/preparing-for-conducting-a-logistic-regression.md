---
title: "Preparing for Conducting a Logistic Regression"
date: 2021-02-02T11:22:57+01:00
draft: false
categories: ["Research methodology", "Subject expertise"]
---

In a meeting with SS, he explained to me that in order to conduct a logistic regression a few preparatory steps are needed. After talking to him, I also started reeding up on logistic regression in the book SPSS Survival Manual (7th ed.) by Julie Pallant. To summarize, the following steps needs to be taken before you can conduct a logistic regression: 1) Motivate the predictors (independant variables) chosen; 2) Make sure assumptions are met; 3) Prepare the data.

### 1. Motivate the predictors chosen

Firstly, one needs to decide on which predictors to include and motivate why they should be included. This should be motivated theoretically based on what is known through earlier research in the field. 

#### 1.1. Predictors chosen for the logistic regression
As in my case, after discussing with SS I decided to add 'Earlier experience of being actively involved in research' as an additional predictor to the list of already decided-upon predictors. Thus, the list of predictors (independant variables) for willingness to be actively involved in research decided-upon that I would like to include in the model are (with the variable names in SPSS in parenthesis):
##

* Age (AGE)
* Sex (GENDER) 
* Level of education (Q19_recode)
* Economic situation (Q21) 
* Self-rated health (Q27)
* Birthplace ("Är du född i ett annat land än Sverige) (Q22)
* Kommunklassificering (MunicipalityClassification)
* Earlier experience of being actively involved in research (ActivelyInvolved)

For the lastly listed independant variable, I realised that I needed to create a new variable which goes something like this:
  
IF Q3._1_recode V Q3._2_recode V Q3._3_recode V Q3._4_recode V Q3._5_recode V Q3._6_recode V Q3._7_recode = 1 --> Have been actively  involved in research = 1. 

Thus, for this created a new variable called *ActivelyInvolved* (through Transform -> Compute variable as described [here](https://archive.fo/I3N7R) as 'Method 2'). And it worked out just fine!

I also entered manually a '99' for all the cases for which Q3._1_recode AND Q3._2_recode AND Q3._3_recode AND Q3._4_recode AND Q3._5_recode AND Q3._6_recode AND Q3._7_recode = 99. 

Unfortunately, I found no way to in an automatic way enter a '2' for the rest of the answrs so I had to put it in manually.


### 2. Make sure assumptions are met

Secondly, the assumptions must be met in order for the results to be valid. Assumptions here relate to three aspects: a) Sample size; b) Multicollinearity; c) Outliers.


#### Sample size

Here a potential issue concerns the number of cases in the sample and the number of predictors (independant variables) one wishes to include in the logistic regression model. 

In the book it is recommended to run **Descriptive Statistics** on each of the predictors, and to consider collapsing or deleting categories if they have limited numbers.

My question here is: How do you know if the numbers are limited, and what is considered limited. Is there a form of measure for this?

Update: Aftor doing a bit of reading, I found the following formula on page 155 in Pallants book:

> Tabachnick and Fidell (2013, p. 123) give a formula for calculating sample size requirements, taking into account the number of independent variables that you wish to use: N > 50 + 8*m* (where *m* = number of independent variables).

Thus, for me that number would be: 50 + (8 x 9) = 122.


I decided then to run Descriptive Statistics in SPSS on each of the chosen variables and the result is presented here:

##### Running Descripive Statistics in SPSS

* Overview with focus on frequency

  ![](/images/210206-descriptive-overview.jpg)

* Age (AGE)
  + Scale

  ![](/images/210206-age-pie-chart.jpg)


* Sex (GENDER) 
  + 1 = Man
  + 2 = Kvinna
  
  ![](/images/210206-sex-table.jpg)

* Level of education (Q19_recode)
  + 1 = Grundskola 
  + 2 = Gymnasium 
  + 3 = Eftergymnasial utbildning, mindre än tre år 
  + 4 = Eftergymnasial utbildning, tre år eller mer
  + 5 = Forskarutbildning
  + 6 = Annat/vill ej uppge
  
  ![](/images/210206-education-table.jpg)
  ![](/images/210206-education-pie-chart.jpg)

* Economic situation (Q21) 
  + 1 = Dålig
  + 2 = Någorlunda
  + 3 = God
  + 4 = Mycket god
  + 5 = Utmärkt
  
  ![](/images/210206-economy-table.jpg)
  ![](/images/210206-economy-pie-chart.jpg)
  
  
* Self-rated health (Q27)
  + 1 = Dålig
  + 2 = Någorlunda
  + 3 = God
  + 4 = Mycket god
  + 5 = Utmärkt
  
  ![](/images/210206-self-rated-health-table.jpg)
  ![](/images/210206-self-rated-health-pie-chart.jpg)
  
  
* Birthplace ("Är du född i ett annat land än Sverige") (Q22)
  + 1 = Ja
  + 2 = Nej
  
  ![](/images/210206-country-born-table.jpg)
  ![](/images/210206-country-born-pie-chart.jpg)
  
* Kommunklassificering (MunicipalityClassification)
  + A1 = Large cities
  + A2 = Commuting municipalities near large cities
  + B3 = Medium-sized towns
  + B4 = Commuting municipalities near medium-sized towns
  + B5 = Commuting municipalities with a low commuting rate near medium-sized towns
  + C6 = Small towns
  + C7 = Commuting municipalities near small towns
  + C8 = Rural municipalities
  + C9 = Rural municipalities with a visitor industry
  
  ![](/images/210206-municipality-classification-table.jpg)
  ![](/images/210206-municipality-classification-pie-chart.jpg)
  
* Have been actively involved in research? (ActivelyInvolved)
  + 1 = Yes 
  + 2 = No
  
  ![](/images/210206-active-involvement-table.jpg)
  ![](/images/210206-active-involvement-pie-chart.jpg)

##### Conclusions drawn from running Descripive Statistics in SPSS

* **Age (AGE)**
  
  Since AGE is a scale, the outcome of Descriptic Statistics doesn't really  matter and we do not have to do any edits due to the sample size for this variable.
  
---

* **Sex (GENDER)**
  
  Since the variable GENDER is only has two categories and the division is about 50/50, there is in this case to worry about a too small sample size for this variable. Så kategorierna blir här:
  
  * Man (n=412)
  * Kvinna (n=462)

---

 * **Level of education (Q19_recode)**
 
   Here it becomes a bit trickier. To begin with there are six individuals (0,7 %) who filled in *'Annat, nämligen'*. First and foremost, since they are so few they cannot constitute a standalone category apropriate for the logistic regression. Moreover, the fact that one cannot simply say that the kind of education that these individuals have can be graded along the same  higher-lower level of education scale as the others, they need to be excluded. What code should they be given? I think ideally they should be assigned a special code but in order not to complicate things, I will give them a code '99' (= Missing), since I will anyway just use valid percent for the logistic regression. 
   
   Next, only 18 individuals in the sample has*'Forskarutbildning*, which sounds too little to constitute an independant category in this case. Thus, I will incorporate this category into the existing category 'Eftergymnasial utbildning, tre år eller mer'.
   
   Rather than keeping the categories as they are, due to the characteristics and sample size and how it is divided into categories, I have decided that for the logistic regression, re-code the variable 'Level of education' and lower the number of categories from six to four, namely the following:
   
   * 1 = Grundskola (n=210)
   * 2 = Gymnasium (n=155)
   * 3 = Eftergymnasial utbildning mindre än tre år (n=201)
   * 4 = Eftergymnasial utbildning mer än tre år (n=284 + 18 = 302)
   
   Thus, the recoding I did was the following and I named the new variable *Q19_Recode_for_LR* 
   
   * 1 -> 1 = Grundskola
   * 2 -> 2 = Gymnasium
   * 3 -> 3 = Eftergymnasial utbildning mindre än tre år
   * 4 -> 4 = Eftergymnasial utbildning mer än tre år
   * 5 -> 4 = Eftergymnasial utbildning mer än tre år
   * 6 -> 99 = Missing
   * 7 -> 99 = Missing
   
   <br>
   
   ![](/images/210208-education-table.jpg)
   
   <br>
   
   ![](/images/210208-education-pie-chart.jpg)
  

---

* **Economic situation (Q21)**

  The category 'Dålig' has 46 responses and 'Utmärkt' has 53. I consider both these categories too small to bear the logistic regression. Thus, I will recode the variable to contain the following categories:

  * Dålig - Någorlunda (n = 46 + 226 = 272)
  * God (n = 390)
  * Mycket god - Utmärkt (n = 154 + 53 = 207)
  
  
  Thus, the recoding I did was the following and I named the new variable *Q21_Recode_for_LR_*
  
  * 1 -> 1 = Dålig - Någorlunda
  * 2 -> 1 = Dålig - Någorlunda
  * 3 -> 2 = God
  * 4 -> 3 = Mycket god - Utmärkt
  * 5 -> 3 = Mycket god - Utmärkt
  
  ![](/images/210208-economy-table.jpg)
  ![](/images/210208-economy-pie-chart.jpg)
  
---

* **Self-rated health (Q27)**

  The category 'Dålig' has 22 responses, and 'Utmärkt' has 91. I think at least the former category is too small. Thus, I will recode the variable to contain the following categories:

  * Dålig - Någorlunda (n=22 + 216 = 238)
  * God (n = 338)
  * Mycket god - Utmärkt (n = 210 + 91 = 301)
  
  Thus, the recoding I did was the following and I named the new variable *Q27_Recode_for_LR_*
  
  * 1 -> 1 = Dålig - Någorlunda
  * 2 -> 1 = Dålig - Någorlunda
  * 3 -> 2 = God
  * 4 -> 3 = Mycket god - Utmärkt
  * 5 -> 3 = Mycket god - Utmärkt

  ![](/images/210208-self-rated-health-table.jpg)
  ![](/images/210208-self-rated-health-pie-chart.jpg)

---

* **Birthplace (“Är du född i ett annat land än Sverige") (Q22)**

  Here I think it is motivated to rephrase the question, since a vast majority is born in Sweden and since this could be argued constitute the "normal" case. In other words, I will create a new variable called BornInSweden where 1 = Yes, and 2 = No. Thus the categories for this variable will be 

  * Yes = 799
  * No = 78
  
  Thus, the recoding I did was the following and I named the new variable *Q22_Recode_for_LR_* [Born in Sweden]
  
  * 1 -> 2 = "No"
  * 2 -> 1 = "Yes"

  ![](/images/210208-born-in-sweden-table.jpg)
  ![](/images/210208-born-in-sweden-pie-chart.jpg)
  
---

* **Kommunklassificering (MunicipalityClassification)**

  The current classificaion categories are. However, some of these catagories does not contain such a large amount of respinses. It is hard to know what should be considered to be sufficient in this context, But I drew the line at 123, and thus decided to recode the variable so that it contains the following six categories instead of the prevailing nine:

  * A1 = Large cities (n=134)
  * A2 = Commuting municipalities near large cities (n=134)
  * B3 = Medium-sized towns (n=195)
  * B4 + B5 = Commuting municipalities near medium-sized towns (n=95 + 58 = 153)
    * C6 = Small towns (n=123)
  * C7 + C8 + C9 = Commuting municipalities near small towns OR Rural municipalities (n=70 + 65 = 135)

  Here, I also realised that it is preferrable to have a data set that has simple numbers, rather than codes, so I first create a new variable called *MunicipalityClassification_numbers* in which I deleted the initial letter in the code, so that A1 -> 1; A2 -> 2; B3 -> 3, etc.
  
  Thus, the recoding I did was the following and I named the new variable *MunicipalityClassification_Recode_for_LR_*
  
  * 1 -> 1 = A1: Large cities
  * 2 -> 2 = A2: Commuting municipalities near large cities
  * 3 -> 3 = B3: Medium-sized towns
  * 4 -> 4 = B4 + B5: Commuting municipalities near medium-sized towns
  * 5 -> 4 = B4 + B5: Commuting municipalities near medium-sized towns
  * 6 -> 5 = C6: Small towns
  * 7 -> 6 = C7 + C8 + C9: Commuting municipalities near small towns OR Rural municipalities
  * 8 -> 6 = C7 + C8 + C9: Commuting municipalities near small towns OR Rural municipalities
  * 9 -> 6 = C7 + C8 + C9: Commuting municipalities near small towns OR Rural municipalities
  
  ![](/images/210208-municipality-classification-table.jpg)
  ![](/images/210208-municipality-classification-pie-chart.jpg)

---

* **Have been actively involved in research? (ActivelyInvolved)**

  Only two categories and 119 responses (13.5%) in the smallest one, so not so much to speak about. However, I decided to assign a '0' to the non-active involvment and a '1' to the active involvement.  Thus, the recoding I did was the following and I named the new variable *ActivelyInvolved_recode_for_LR_*:

  * 1 -> 1 = Yes
  * 2 -> 0 = No

  ![](/images/210208-active-involvement-table.jpg)
  ![](/images/210208-active-involvement-pie-chart.jpg)

---
  
* **In summary**

Birthplace has only 78 responses in the 'No' category, which is judging by the formula for multiple regression too small a number. The question is if this requirement need to be fulfilled also when running logistic regression. Is it better then to create two different models then rather than one big? In order for an N = 78 to be acceptable in a model it can at most contain *m* independant variables, where:

78 < OR = 50 + 9*m*

Meaning, it could at most contain three independent variables.



<!-- Regarding willingness to be actively involved in research on ageing and health, when asked the question “Would you consider being actively involved in research on ageing and health?”, 41% responded that it was something they would consider, 27% that it was something they might consider and 32% responded that it was something they did not consider.  --> 
  

#### Multicollinearity

On page 136, Pallant writes:

> Before performing a correlation analysis, it is a good idea to generate a scatterplot. This enables you to check for outliers and for violation of the assumptions of linearity. [...] Inspection of the scaterplots also gives you a better idea of the nature of the relationship between your variables.

The question is, which variables should I check for correlation between? Can I do it for all eight independent variables as once? As I read further in the book, this is possible following the method described on page 143. However, intertwining too many variables like that is not without cautions, and it is good to have a strategy or plan for what one is doing and why. I also found [a good article](https://archive.fo/0M2DF) on Medium on the topic. <!--https://medium.com/@outside2SDs/an-overview-of-correlation-measures-between-categorical-and-continuous-variables-4c7f85610365--> However, following the instructions given in the chapter in Pallant's book devoted specifically to logistic regression, she writes (on page 176):

> ...you should always check for high intercorrelation among your predictor (independent) variables. Ideally, your predictor variables will be strongly related to your dependent variable but not strongly related to each other. Unfortunately, there is no formal way in the logistic regression procedure of IBM SPSS Statistics to test for multicollinearity, but you can use the procedure described in Chapter 13 to request **collinearity diagnostics** under the **Statistics** button. Ignore the rest of the output, but focus on the **Coefficients table** and the columns labelled **Collinearity Statistics**. Toleranc values that are very low (less than .1) indicate that the variable has high correlations with other variables in the model. You may need to reconsider the set of variables that you wish to include in the model and remove one of the highly intercorrelating variables.

I followed the instructions on page 169 and this was the **Coefficients table** I got:

![](/images/210208-coefficients-table.jpg)

<!--
What then - theoretically speaking - could potentially be correlated? Here I will do some speculation:
 
##### Age (AGE) vs. Self-rated health (Q27_Recode_for_LR_)(continous - categorical)
I suppose that *Age** and *Self-rated health* is the most obvious one. Their correlation looks like this:

##### Self-rated health (Q27_Recode_for_LR_) vs. Economic situation (Q21_Recode_for_LR_)(categorical - categorical)
There is also a possible correlation betwen *Self-rated health* and *Economic situation*.  Their correlation looks like this:

##### Age (AGE) vs. Level of education (Q19_Recode_for_LR)(continous - categorical)
Another possible correlation is between *Age* and *Level of eduation*. Their correlation looks like this:

##### Age (AGE) vs. Economic situation (Q21_Recode_for_LR_) (continous - categorical)
There is a potential correlation between *Age* and *Economic situation*. Their correlation looks like this:

##### Self-rated health (Q27_Recode_for_LR_) vs. Level of education (Q19_Recode_for_LR) (categorical - categorical)
Another potential correlation is the one between *Self-rated health* and *Level of education*. Their correlation looks like this:

##### Level of education (Q19_Recode_for_LR_) and Economic situation (Q21_Recode_for_LR_)
There is also a possible correlation beteen *Level of education* and *Economic situation*. Their correlation looks like this:

##### Kommunklassificering (MunicipalityClassification_Recode_for_LR_) and Self-rated health (Q27_Recode_for_LR_)
Another potential correlation could be between *Kommunklassificering* and *Self-rated health*. Their correlation looks like this:

##### Kommunklassificering (MunicipalityClassification_Recode_for_LR_) and Economic situation (Q21_Recode_for_LR_)
There is also a possibble correlation between *Kommunklassificering* and *Economic situation*. Their correlation looks like this:

##### Kommunklassificering (MunicipalityClassification_Recode_for_LR_) and Level of education (Q19_Recode_for_LR)
Another potential coorrelation could be betwen *Kommunklassificering* and 
*Level of education*. Their correlation looks like this:

##### Age (AGE) and Kommunklassificering (MunicipalityClassification_Recode_for_LR_)
* There is also a potential correlation between *Age* and *Kommunklassificering* Their correlation looks like this:

As for *Sex*, *Birthplace* and *Have been actively involved in research?*, these variables contain only two categories, which I judge are too few categories to have a potential to be correlated to any other variables. -->


---

#### Outliers
Pallant writes on page 176:

> It is important to check for presence of outliers or cases that are not well explained by your model. In logistic regression terms, a case may be strongly predicted by your model to be one category but in reality be classfied in the other category. These outlying cases can be identified by inspecting the residuals, a particularly important step if you have problems with the goodness of fit of your model.

Here is the **Residuals table** I got when I follwed to instructions on page 169:

![](/images/210208-residuals-statistics-table.jpg)


---


### 3. Prepare the data

Here, I need to make the dependent variable dichotomous, and not only that, I should also according to Pallant (p. 177)...

> ...code the responses as O and 1 [...] The value of 0 should be assigned to whichever response indicate a lack or absence of the characteristic of interest.

The dependent variable is here *Q7 Skulle du kunna tänka dig att medverka aktivt i forskning om åldrande och hälsa?*, which currently is coded in the following way:

* 1 = Ja
* 2 = Nej
* 3 = Kanske

In order to code it properly for the logistic regression I recoded it in the following way and I named the new variable *Q7_recode_for_LR_*:

* 1 -> 1
* 2 -> 0
* 3 -> 1

  ![](/images/210208-dependent-variable-table.jpg)
  ![](/images/210208-dependent-variable-pie-chart.jpg)






