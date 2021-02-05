---
title: "Preparing for Conducting a Logistic Regression"
date: 2021-02-02T11:22:57+01:00
draft: false
categories: ["Research methodology", "Subject expertise"]
---

In a meeting with SS, he explained to me that in order to conduct a logistic regression a few preparatory steps are needed. After talking to him, I also started reeding up on logistic regression in the book SPSS Survival Manual (7th ed.) by Julie Pallant. To summarize, the following steps needs to be taken before you can conduct a logistic regression: 1) Motivate the predictors (independant variables) chosen; 2) Make sure assumptions are met; 3) Prepare the data.

### 1. Motivate the predictors (independant variables) chosen

Firstly, one needs to decide on which predictors to include and motivate why they should be included. This should be motivated theoretically based on what is known through earlier research in the field. As in my case, after discussing with SS I decided to add 'Earlier experience of being actively involved in research' as an additional predictor to the list of already decided-upon predictors. Thus, the list of predictors (independant variables) for willingness to be actively involved in research decided-upon that I would like to include in the model are (with the variable names in SPSS in parenthesis):

* Age (AGE)
* Sex (GENDER) 
* Level of education (Q19_recode)
* Economic situation (Q21) 
* Self-rated health (Q27)
* Birthplace ("Är du född i ett annat land än Sverige) (Q22)
* Municipality classification (MunicipalityClassification)
* Earlier experience of active involvement (ActivelyInvolved)

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

Anyways, I decided to run Descriptive Statistics in SPSS on each of the chosen variables and the result is presented [here]()

* Age (AGE)
  + Scale
* Sex (GENDER) 
  + 1 = Man
  + 2 = Kvinna
* Level of education (Q19_recode)
  + 1 = Grundskola 
  + 2 = Gymnasium 
  + 3 = Eftergymnasial utbildning, mindre än tre år 
  + 4 = Eftergymnasial utbildning, tre år eller mer
  + 5 = Forskarutbildning
  + 6 = Annat/vill ej uppge
* Economic situation (Q21) 
  + 1 = Dålig
  + 2 = Någorlunda
  + 3 = God
  + 4 = Mycket god
  + 5 = Utmärkt
* Self-rated health (Q27)
  + 1 = Dålig
  + 2 = Någorlunda
  + 3 = God
  + 4 = Mycket god
  + 5 = Utmärkt
* Birthplace ("Är du född i ett annat land än Sverige) (Q22)
  + 1 = Ja
  + 2 = Nej
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
  
* Have been actively involved in research (ActivelyInvolved)
  + 1 = Yes 
  + 2 = No

#### Multicollinearity


#### Outliers



### 3. Prepare the data
