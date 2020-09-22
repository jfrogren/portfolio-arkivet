## Data cleaning questions for study II
Here are notes related to the data set for the questions in the survey: 

### Weight
* What does 'Weight' mean here?

### CHANNEL
* What does channel 1, 2 and 3 mean? I understand that they refer to the medium through which the interview was made but what number means what medium?

### LK
* What does 'LK' mean?
* INTNR 206 has no value in LK. What does that mean?

### Gender
* In six cases (INTNR 206; 556; 580; 642; 687; 693) gender is missing. How to deal with that?

### Age
* In six cases (INTNR 206; 556; 580; 642; 687; 693) is missing. How to deal with that?

### Q1
* Some have filled in '2' for 'No', while some have left blank for 'No'. Have these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q1_1-6 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* For INTNR 258, 278, 298, 333, 369, 447,  540, 568, 603 and 660, the questions Q1_1-6 are left blank, and considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* For INTNR 66, Q1.6 is left blank but there is still a Q1_Other reply to the question (meaning it should be a '1' instead of left blank). How to treat this? Should I insert a '1' there? 
* For INTNR 576 Q1.6 is a '1', but the Q1_Other answer says 'No'. How to treat this? I suggest filling in a '2' instead of '1' on Q1.6.
* INTNR 6, 313, 317, 319, 383, 516, 634, 857 have answered '1' but given no Q1_Other answer. Should that pass as a '1' still? Why is this and what where the instructions given?
* When it comes to Q1_Other, some of the free-text answers constitute - as intended - additional, not earlier mentioned alternatives. Others contain to little information which makes it not possible to interpret/understand sufficiently while others does in fact correspond to an already existing given alternative (Q1.1-5). I suggest that the answers of the following INTNR's free-text answers are catagories in the following way:
 
  + INTNR 369; 615; 818 --> New additional alternative
  + INTNR 66; 68; 131; 198; 293; 375; 477; 674; 712; 729; 738; 739; 759; 761; 775; 808 --> Not enough info to understand 
  
  + INTNR 19 --> Q1_4
  + INTNR 27 --> Q1.2
  + INTNR 64 --> Q1_1
  + INTNR 136 --> Q1_5
  + INTNR 149 --> Q1.2 or Q1.4
  + INTNR 190 --> Q1.1 + Q1.3
  + INTNR 195 --> Q1.2
  + INTNR 220 --> Q1.2
  + INTNR 239 --> Q1.5
  + INTNR 295 --> Q1.1
  + INTNR 349 --> Q1.2
  + INTNR 364 --> Q1.5
  + INTNR 465 --> Vad räknas 'Tvilingstudien' som?
  + INTNR 490 --> Q1_2
  + INTNR 512 --> Vad räknas 'Gott åldrande i Skåne' till? Q1.1, Q1.3, Q1.4, Q1.5?
  + INTNR 545 --> Personen har själv forskat (varit forskare). Hur kategorisera?
  + INTNR 599 --> Q1.1
  + INTNR 607 --> Vad räknas 'Monicaprojektet' om hjärt- och kärlsjukdomar till?
  + INTNR 701 --> Q1_1
  + INTNR 721 --> Q1.4
  + INTNR 777 --> Q1.1
  + INTNR 830 --> Q1.3
  + INTNR 851 --> Hur ska 'Som undersökare' klassificeras? 'Not enough info to understand' eller 'New additional alternative'?
  
  
### Q2
* Is '1'=Yes; '2'=No and '3'=Tveksam/vet ej?
* Missing data for INTNR 568 and 613. Include these missing values in the analysis of the question?

### Q3
* Some have filled in '2' for 'No', while some have left blank for 'No'. Has these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q3_1-7 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* For INTNR 92; 109; 178; 228; 258; 298; 333; 407; 447; 540; 557; 568; 603; 660; 692, the questions Q3_1-7 are left blank, and considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* INTNR 375 and 634 have answered '1' but given no Q3_Other answer. Should that pass as a '1' still?
* When it comes to Q3_Other, some of the free-text answers constitute in fact additional, not earler mentioned alternatives. Others contain to little information which makes it not possible to interpret/understand sufficiently while others does in fact correspond to an already existing given alternative (Q3.1-6). I suggest that the answers of the following INTNR's free-text answers are catagories in the following way:

  + INTNR 261; 484 --> New additional alternative
  + INTNR 34; 99; 193; 244; 280; 324; 337; 356; 477; 518; 576; 591; 650; 658; 671; 709 --> Not ACTIVE participation the way defined here
  + INTNR 68; 76; 239; 550; 555; 604; 739; 775 --> Not enough info to understand 
  + INTR 6; 545 --> The answer indicates that the whole question Q3.1-7 have not been properly understood by participant. I suggest not include these persons answers in the analysis.
  
  + INTNR 278 --> Should it be considered as Q3.6 or is it NOT active participation in research? I lean towards the latter.
  + INTNR 539 --> Either 'Not enough information to understand' or NOT active participation the way we define it.
  + INTNR 545 --> Personen har själv forskat (varit forskare). Hur svarat på frågorna utifrån forskarrollen ej som 'privatperson'. Hur kategorisera?
  + INTNR 853 --> Q3.6
  + INTNR 326 --> Q3.4
  + INTNR 617 --> Q3.1 + 3.2
  

### Q4 

* There seems to be three different reply alternatives here: '1', '2' and '3'. What do they refer to?
* Some have filled in '2' for 'No', while some have left blank for 'No'. Has these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q4_1-11 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* For INTNR 12; 13; 20; 24; 25; 32; 39; 44; 46; 61; 65; 74; 82; 92; 94; 95; 102; 103; 109; 135; 138; 148; 151; 178; 180; 204; 208; 210; 216; 228; 230; 237; 243; 258; 263; 268; 271; 288; 291; 298; 310; 330; 333; 334; 342; 344; 358; 371; 391; 393; 407; 410; 412; 419; 421; 434; 455; 460; 465; 497; 506; 509; 527; 530; 543; 557; 559; 563; 568; 603; 611; 623; 624; 643; 655; 660; 665; 668; 678; 685; 692; 696; 702; 718; 724; 727; 731; 738; 745; 749; 753; 761; 768; 794; 795; 801; 804; 814; 819; 830; 833; 872, the questions Q4.1-12 are left blank. Is it because these participants have answered in a way in the former question that they are told not to answer this question, or considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* For INTNR 400; 864, the question Q4.12 is left blank but there is still a Q4_Other reply to the question (meaning it should be a '1' instead of left blank). How to treat this? Should I insert a '1' there? 

#### Q4_Other
* When it comes to Q1_Other, some of the free-text answers constitute - as intended - additional, not earlier mentioned alternatives. Others contain too little information which makes it impossible to interpret/understand sufficiently. Others again does in fact correspond to an already existing given alternative (Q1.1-5). I suggest that the answers of the following INTNR's free-text answers are categories in the following way:
##### New additional alternatives
* 370
* 600
* 399
* 864
* 220
* 292
* 478
* 300
* 404
* 488
* 209


##### Not enough info to understand/ answer does not correspond to question 
* 516
* 313
* 644
* 131
* 184
* 53
* 357
* 293
* 289
* 105
* 857
* 400


##### Uncertain where the alternatives belong
* 825
* 733
* 691
* 129

##### Correspond to already existing alternatives 
* 149 --> Q4.8
* 734 --> Q4.1
* 528 --> Q4.1
* 779 --> Q4.7
* 377 --> Q4.11
* 859 --> Q4.7
* 58 --> Q4.11
* 31 --> Q4.11
* 564 --> Q4.11
