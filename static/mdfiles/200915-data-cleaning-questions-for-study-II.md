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
* When it comes to Q1_Other, some of the open question answers constitute - as intended - additional, not earlier mentioned alternatives. Others contain to little information which makes it not possible to interpret/understand sufficiently while others does in fact correspond to an already existing given alternative (Q1.1-5). I suggest that the answers of the following INTNR's open answers answers are categories in the following way:
 
##### New additional alternatives
* INTNR: 
  + 369
  + 615
  + 818

##### Not enough info to understand 
* INTNR: 66; 68; 131; 198; 293; 375; 477; 674; 712; 729; 738; 739; 759; 761; 775; 808

##### Correspond to already existing alternatives 
* INTNR: 
  + 64 --> Q1_1
  + 190 --> Q1.1 + Q1.3
  + 295 --> Q1.1
  + 599 --> Q1.1
  + 701 --> Q1_1
  + 777 --> Q1.1
  + 27 --> Q1.2
  + 149 --> Q1.2 or Q1.4
  + 195 --> Q1.2
  + 220 --> Q1.2
  + 349 --> Q1.2
  + 490 --> Q1_2
  + 830 --> Q1.3
  + 19 --> Q1_4
  + 721 --> Q1.4
  + 136 --> Q1_5
  + 239 --> Q1.5
  + 364 --> Q1.5
  
##### Uncertain where the alternatives belong
* INTNR:
  + 465 --> Vad räknas 'Tvillingstudien' som?
  + 512 --> Vad räknas 'Gott åldrande i Skåne' till? Q1.1, Q1.3, Q1.4, Q1.5?
  + 545 --> Personen har själv forskat (varit forskare). Hur kategorisera?
  + 607 --> Vad räknas 'Monicaprojektet' om hjärt- och kärlsjukdomar till?
  + 851 --> Hur ska 'Som undersökare' klassificeras? 'Not enough info to understand' eller 'New additional alternative'?
  
  
### Q2
* Is '1'=Yes; '2'=No and '3'=Tveksam/vet ej?
* Missing data for INTNR 568 and 613. Include these missing values in the analysis of the question?

### Q3
* Some have filled in '2' for 'No', while some have left blank for 'No'. Has these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q3_1-7 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* For INTNR 92; 109; 178; 228; 258; 298; 333; 407; 447; 540; 557; 568; 603; 660; 692, the questions Q3_1-7 are left blank, and considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* INTNR 375 and 634 have answered '1' but given no Q3_Other answer. Should that pass as a '1' still?
* When it comes to Q3_Other, some of the open question answers constitute in fact additional, not earler mentioned alternatives. Others contain to little information which makes it not possible to interpret/understand sufficiently while others does in fact correspond to an already existing given alternative (Q3.1-6). I suggest that the answers of the following INTNR's open question answers are categories in the following way:

#### New additional alternatives
* INTNR: 
  + 261
  + 484 

#### Not ACTIVE participation the way defined here
* INTNR: 34; 99; 193; 244; 280; 324; 337; 356; 477; 518; 576; 591; 650; 658; 671; 709 --> 

#### Not enough info to understand/ answer does not correspond to question 
* INTNR: 68; 76; 239; 550; 555; 604; 739; 775

#### Answers indicate whole question misunderstod
* INTNR: 6; 545 --> The answer indicates that the whole question Q3.1-7 have not been properly understood by participant. I suggest not include these persons answers in the analysis.

#### Uncertain where the alternatives belong
* INTNR: 
  + 278 --> Should it be considered as Q3.6 or is it NOT active participation in research? I lean towards the latter.
  + 539 --> Either 'Not enough information to understand' or NOT active participation the way we define it.
  + 545 --> Personen har själv forskat (varit forskare). Hur svarat på frågorna utifrån forskarrollen ej som 'privatperson'. Hur kategorisera?

#### Correspond to already existing alternatives 
* INTNR:
  + 853 --> Q3.6
  + 326 --> Q3.4
  + 617 --> Q3.1 + 3.2
  

### Q4_1-1 

* There seems to be three different reply alternatives here: '1', '2' and '3'. What do they refer to?
* Some have filled in '2' for 'No', while some have left blank for 'No'. Has these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q4_1-11 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* For INTNR 12; 13; 20; 24; 25; 32; 39; 44; 46; 61; 65; 74; 82; 92; 94; 95; 102; 103; 109; 135; 138; 148; 151; 178; 180; 204; 208; 210; 216; 228; 230; 237; 243; 258; 263; 268; 271; 288; 291; 298; 310; 330; 333; 334; 342; 344; 358; 371; 391; 393; 407; 410; 412; 419; 421; 434; 455; 460; 465; 497; 506; 509; 527; 530; 543; 557; 559; 563; 568; 603; 611; 623; 624; 643; 655; 660; 665; 668; 678; 685; 692; 696; 702; 718; 724; 727; 731; 738; 745; 749; 753; 761; 768; 794; 795; 801; 804; 814; 819; 830; 833; 872, the questions Q4.1-12 are left blank. Is it because these participants have answered in a way in the former question that they are told not to answer this question, or considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* For INTNR 400; 864, the question Q4.12 is left blank but there is still a Q4_Other reply to the question (meaning it should be a '1' instead of left blank). How to treat this? Should I insert a '1' there? 

### Q4_Other
* When it comes to Q1_Other, some of the open question answers constitute - as intended - additional, not earlier mentioned alternatives. Others contain too little information which makes it impossible to interpret/understand sufficiently. Others again does in fact correspond to an already existing given alternative (Q1.1-5). I suggest that the answers of the following INTNR's open question answers are categorised in the following way:

#### New additional alternatives
* INTNR:
  + 370
  + 600
  + 399
  + 864
  + 220
  + 292
  + 478
  + 300
  + 404
  + 488
  + 209


#### Not enough info to understand/ answer does not correspond to question 
* INTNR: 53; 105; 131; 184; 289; 293; 313; 357; 400; 516; 644; 857


#### Uncertain where the alternatives belong
* 825
* 733
* 691
* 129

#### Correspond to already existing alternatives 
* 149 --> Q4.8
* 734 --> Q4.1
* 528 --> Q4.1
* 779 --> Q4.7
* 377 --> Q4.11
* 859 --> Q4.7
* 58 --> Q4.11
* 31 --> Q4.11
* 564 --> Q4.11

### Q5
* Ingenting att kommentera här. I de fall där värde saknas är det 'Missing value', i övriga fall de alternativ som har angetts.

### Q6
* Ingenting att kommentera här. I de fall där värde saknas är det 'Missing value', i övriga fall de alternativ som har angetts.

### Q7
* Denna fråga har 'missing value' för cirka sju deltagare. Hur kommer det sig att dessa är missing. Denna fråga borde vara nödvändig att svara på för att kunna gå vidare. Ska jag titta på vilken som är nästkommande fråga som deltagaren har svarat på och fylla i 1-3 baserat på det? 

### Q8a-f
* Här finns fem svarsalternativ, men i många fall finns siffran '6' angiven. Det beror på att på den föregående frågan 7 har dessa svarat '2' och därmed hoppat till fråga 11. Bör dessa svar räknas som 'Missing' eller hur ska '6' kodas? 
* För vissa INTNR (161; 375; 782; 856) är 8a-f lämnat blankt istället för att '6' har angetts. Ska dessa kodas som '6' för enhetlighetens skull? Spelar det någon roll?

### Q8g
* Participants who have a '2' on Q7 and a '6' on Q8a-f, here have a '3'. What label should '3' be given?
* 155 participants have a '-' here followed by nothing written in free-text, should this be interpreted as a '2' (= No) or should it be interpreted as a 'Missing value'?
* Of the 184 participants who have answered '1', about 45 participants have in the free-text a text that says 'Nej', Inget' or 'Inget direkt' or 'Alla frågor täckta'. I suggest that for these answers, the '1' is replaced by a '2'.
* Of the 184 participants who have answered '1' about 15-20 participants have in the free-text written 'Vet inte..', 'Kanske beror på', 'Om jag ser något ämne som är intressant', 'måste fundera på det', 'kan om tid finns', 'svårt att säga', 'svårt att svara på', 'om det är något jag finner viktigt...kan jag tänka mig'. This indicates that a simple Yes/No answer to this question was maybe the wrong options to provide, or maybe the questions hould have been formulated differently? Maybe the participants should have been given more options. At  minimum a 'Vet inte' option. To illustrate the difficulty of answering the question a "quote" from one of the participants can be given. He/she (as interpreted by the interviewer) that "Frågeställningarna är så svepande. När forskningen preciseras kan frågan ovan besvars". Another quote is "Nej, det är ju väldigt svårt att säga när man vet så lite om det". How to deal with these replies?  
* To complicate things further, out of the ones who have answered '1' but written 'Nej', many have written 'Nej, jag vet inte...', which is a reply somewhere in between 'Nej' and 'Vet inte'. How to code or categorize these free-text answers?
* One participant has a '1' but then nothing written in free-text. How should that data be interpreted and coded?
* Out of the remaining '1' answers (after the 'Nej' and 'Vet inte' issues have been dealt with), the remaining free-text answers can be divided into the following categories:

#### New additional alternatives
* 60 ('Jag skulle tänka mig att intervjua') --> 8c
* 555 (= många olika förslag)
* 296; 439; 443; 560; 725; 864 ('Ge synpunkter på ett frågeformulär') --> 8a
* 350 ('Sprida information på en arbetsplats') -->8e
* 490 ('Sprida kunskap till vänner och bekanta') -->8e
* 360 ('Bidra med förslag till forskningsområden') -->8a
* 190 ('Kan tänka mig att telefonintervjua, åka runt och intervjua, sammanställa och utvärdera resultat, etc.') -->8c + 8d
* 390 ('Genom att driva vissa frågor gällande pensionärer')
* 520 ('Kunna informera i olika typer av grupper, både yngre och äldre, föreningar och andra typer av grupper i hennes närhet') -->8e
* 143 ('Komma med synpunkter på de resultaten som publiceras som just handlar om åldrande och hälsa') -->8e
* 259 ('Gå på föreläsningar, lyssna online. Prata om de med andra människor')
* 709 ('Berätta om mina erfarenheter med åldrande föräldrar...relaterat till mitt eget åldrande')
* 402 ('Kommunikationsmässigt, via nät eller media. Eller artiklar i tidningen')
* 735 ('Ingå i en arbetsgrupp där olika frågor diskuteras') -->8b
* 775 ('Inringa forskningsområden') -->8a
* 321 ('delta i diskussionsgrupp') -->8b
* 699 ('distribuera information') -->8e
* 875 ('Att informera inom PRO eller annan orgnisation') -->8e
* 250 ('Informera på pensionärsträffar t.ex.') -->8e
* 196 ('Van att läsa långa texter och utredningar och kan bidra med något liknande')
* 562 ('Jag skulle kunna sprida information i pensionärsföreningarna') -->8e
* 253 ('skulle kunna fråga en grupp äldre, typ ca 10 pers om aktuella frågor som är intressanta fr målgruppen') -->8a?
* 48 ('(Delta i) diskussionsgrupper') -->8b?

##### It depends on...
* location (INTNR 580 ('Endast i närområdet'))
* medium 
  + (INTNR 235 ('gärna genom inlägg på sociala medier som facebook, instagram, twitter'))
  + (INTNR 712 ('om det är samtal'))
  + (INTNR 326 ('Utföra telefonintervjuer'))
* focus
  + (if person finds it interesting/ important (INTNR 6; 102; 861))
  + (INTNR 423 ('Troligen mer intresserad att medverka om man har egen eller närstående sjukdom'))
  + (INTNR 103 ('Det är väl främst frågor som berör sådant jag själv råkat ut för...')
  + (INTNR 414 ('Problem och forskning angående sköldkörteln'))
* time 
  + INTNR 184 ('Kan om tid finns')
  + INTNR 600 ('Om man kunde hjälpa forskare i ett tidigt skede innan saker är bestämt. Det är så man skulle kunna påverka.')
* money (INTNR 503 ('Vill endast deltaga om ersättning utgår')
* knowledge/information (INTNR 409 ('..måste ha baskunskaper, informera tydligt på vilka premisser...sätta sig in i området'))

##### Not enough info to understand/ answer does not correspond to question 
* INTNR: 11; 17; 13; 107; 124; 128; 144; 180; 265; 358; 370; 430; 448; 460; 478; 490; 494; 507; 514; 558; 575; 580; 604; 613; 670; 689; 738; 739; 740; 751; 765; 772; 832; 866

#### Not ACTIVE participation the way defined here
* INTNR: 3; 28; 30; 41; 118; 148; 153; 198; 203; 232; 267; 268; 281; 292; 347; 422; 432; 511; 544; 545; 586; 590; 614; 625; 636; 650; 697; 705; 804; 809

#### Uncertain where the alternatives belong
* INTNR:
  * 35 ('T.ex. vara med och ge synpunkter på medicin/infusion som jag själv använder') - The forms for such an exchange decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation.
  * 46 ('det är väl att man sprider det i sin krets och debatterar privat om olika resultat inom sådan forskning')
  * 53 ('Genom enkäter, helst via internet') - oklart om det åsyftas att svara på eller utforma enkäter
  * 83 ('Frågor till mig om hur jag som äldre mår och hur jag lever')
  * 99 ('Enkäter, provtagningar eller tester') - Not clear if the person means participating in creating/giving  or receiving/answering.
  * 111 ('Delta i utvärderingar i första hand via internet') - The forms for such 'evaluations' decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation.
  * 460 ('Ja genom telefonintervjuer och enkäter') - Unclear if person means conduct these interviews or participate in them
  * 538 ('jag skulle kunna tänka mig att vara med i ett grupparbete')
  * 578 ('genom frågeformulär') - oklart om det åsyftas att svara på eller utforma frågeformulär
  * 602 ('att bli intervjuad i dessa frågorna')
  * 624 ('dela ut flygblad')
  * 833 ('hjälpa till med att svara på frågor') - The forms for 'answering questions' decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation.


#### Correspond to already existing alternatives 
See 'New additional alternatives' for suggestions

### Q9
* Some have filled in '2' for 'No', while some have left blank for 'No'. Have these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q1_1-6 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* Hove should I code the answer '3'
* For INTNR 161; 230; 280; 342; 375; 414; 782; 797; 806; 856, the questions Q9_1-10 are left blank, and considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* For INTNR 320; 414; 775; 806, Q9.10  is left blank but there is still a Q9_Other reply to the question (meaning it should be a '1' instead of left blank). How to treat this? Should I insert a '1' there? 
* When it comes to Q9_Other, some of the open question answers indicate that some participants were not interested in getting information in any way (even if they hav replied in Q7 they they 'would be' interested to participate). How should that data be handled? That goes for the following participants:
  + 825 ('Är inte särskilt intresserad vara med denna gången i och med att vi ringde')
  + 456 ('inget')
  + 806 ('Inte alls')
  + 280 ('Inte på något annat sätt')

* When it comes to Q9_Other, some of the open question answers constitute - as intended - additional, not earlier mentioned alternatives. Others contain too little information which makes it not possible to interpret/understand sufficiently while others does in fact correspond to an already existing given alternative (Q9.1-9). I suggest that the answers of the following INTNR's open question answers are catagories in the following way:

#### New additional alternatives
* INTNR:
  + 181 ('Genom föreningslivet')
  + 555 ('olika mötesplatser')
  + 136 ('muntligt via sociala nätverk')
  + 853 ('via vänner och bekanta')
  + 590 ('Jag vill ha information som är väldigt riktad till mig som individ och inte till för stora grupper')
  + 184 ('det bästa är via läkare')
  + 402 ('Samtalsgrupp t.ex.')
  + 775 ('"webinar"')
  + 220 ('via program som 'Fråga doktorn')
  + 414 ('Genom VC, "min" läkare')
  + 733 ('Uppsökande verksamhet')
  + 330 ('Information i hissar')
  + 723 ('Att pensionärsorganisationer ger information om att man kan medverka aktivt')
  + 320 ('Vid läkarbesök')

#### Correspond to already existing alternatives 
* INTNR:
  + 641 ('Jag tror att skickar man ut brev till alla äldre och saker per post..så kommer fler att delta') --> Q9a
  + 390 ('Genom personligt besök') --> Q9d
  
### Q10
* Some have filled in '2' for 'No', while some have left blank for 'No'. Have these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q1_1-6 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* How should I code the answer '3'
* For INTNR 161; 230; 375; 512; 782 , the questions Q10_1-9 are left blank, and considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* For INTNR 113; 505, the question Q10.9  is left blank but there is still a Q10_Other reply to the question (meaning it should be a '1' instead of left blank). How to treat this? Should I insert a '1' there? 
* When it comes to Q10_Other, some of the open question answers indicate that some participants would have like to have a 'I dont know/ Not certain' option. Here are a list of those participants:
  + INTNR 757 ('Ingen åsikt')
  + INTNR 525 ('vet ej')
* When it comes to Q10_Other, some of the open question answers indicate that some participants were not interested in getting information in any way (even if they have replied in Q7 they they 'would be' interested to participate). How should that data be handled? That goes for the following participants:
  + 825 ('vill inte bli kontaktad alls')
  + 280 ('Inte (heller) på något annat sätt')

* When it comes to Q9_Other, some of the open question answers constitute - as intended - additional, not earlier mentioned alternatives. Others contain too little information which makes it not possible to interpret/understand sufficiently while others does in fact correspond to an already existing given alternative (Q9.1-9). I suggest that the answers of the following INTNR's open question answers are catagories in the following way:

#### New additional alternatives
* INTNR:
  + 356 ('Informativ sida online')
  + 60 ('...från olika myndigheter')
  + 602 ('genom kollegor')
  + 538 ('Människor överlag som man kan lita på, som arbetar utan politisk och ekonomisk vinning')
  + 459 ('Via TV-program som TV-doktorn och Fråga doktorn')
  + 162 ('Fackföreningar')
  + 467 ('Min läkare')
  + 286 ('Facebook')
  

#### Correspond to already existing alternatives 
* INTNR:
  + 590 ('...av Universitetet som driver forskningsprojekt') --> Q10e

#### Uncertain where the alternatives belong
* INTNR:
  + 181 ('Svarar i föregående fråga')
  + 323 ('Det ska vara sjukvårdens forskare som direkt vänder sig till mig för att mina åkommor')
  + 113 ('Där äldre samlas på olika möten, t.ex. på vår [otolkbart] biosalongen eller samlingsal boende')

#### Not enough info to understand/ answer does not correspond to question 
* INTNR:
  + 774 ('Via brev')
  + 368 ('Genom telefonsamtal/telefonintervju')
  + 785 ('Vill helst av allt få information av någon personligen')
  
#### It depends on...
* focus
  + INTNR 555 ('Beror på frågeställningen och målgrupp')
  
#### Not ACTIVE participation the way defined here
* INTNR:
  + 220 ('Vårdcentralen skulle kunna ha enkäter som man kan fylla i')

### Q11
* Ingenting att kommentera här. I de fall där värde saknas är det 'Missing value', i övriga fall de alternativ som har angetts.

### Q12_1-12
* Some have filled in '2' for 'No', while some have left blank for 'No'. Have these different ways of filling in the form to do with whether the interviews were made using a specific medium or is it related to certain individual interviewers? What were the instructions given to SIFO/KANTAR? Here we need to decide if 'blank' or '2' should mean 'No'. Please observe that this is only in cases were at least one of the ansers on the Q12_1-13 is a '1'. For individuals who have no '1' in any of the questions, but only '2' and 'Missing', the '2' will be interpreted as 'No' and 'Missing' as 'Missing'. Isn't that the way to do it?
* For INTNR 174, 806, the questions Q12_1-13 are left blank, and considering the point above, should that be interpreted as 'No' or 'Missing'? How to treat this data?
* For INTNR 135; 161; 367; 781; 851, the question Q12.13  is left blank but there is still a Q12_Other reply to the question (meaning it should be a '1' instead of left blank). How to treat this? Should I insert a '1' there? 
* For INTNR 3; 8; 10; 12; 25; 30; 31; 38; 54; 71; 75; 78; 80; 86; 115; 119; 132; 139; 144; 147; 150; 156; 177; 183; 186; 212; 218; 234; 238; 255; 270; 271; 274; 280; 294; 303; 311; 320; 325; 381; 385; 387; 391; 418; 423; 425; 454; 462; 464; 471; 482; 493; 506; 512; 525; 527; 543; 546; 559; 570; 577; 578; 582; 583; 595; 596; 597; 616; 626; 630; 632; 640; 668; 676; 679; 680; 704; 718; 722; 745; 747; 762; 768; 770; 776; 777; 796; 797; 801; 831; 846; 848; 859; 860; 881 they have answered Q12.13 with a '1' but given no Q12_Other answer. Should that pass as a '1' still? Why is this and what where the instructions given?
* For INTNR 64 they have answered Q12.13 with a '2' but given a Q12_Other answer. Should that pass as a '1'? Why is this and what where the instructions given?

* When it comes to Q12_Other, some of the open question answers indicate that some participants would have like to have a 'I dont know/ Not certain' option. Here is a list of those participants:
  + INTNR
  + INTNR

* When it comes to Q12_Other, some of the open question answers constitute - as intended - additional, not earlier mentioned alternatives. Others contain too little information which makes it not possible to interpret/understand sufficiently while others does in fact correspond to an already existing given alternative (Q12.1-12). I suggest that the answers of the following INTNR's open question answers are catagories in the following way:

#### New additional alternatives
* INTNR:
  + 452 ('...om det handlar om sjukvård och mediciner som blir bättre') --> Q12_9
  + 367 ('ersättning')

#### Correspond to already existing alternatives 
* INTNR:
  + 
  
#### Uncertain where the alternatives belong
* INTNR:
  + 

#### Not enough info to understand/ answer does not correspond to question 
* INTNR:
  + 
  
