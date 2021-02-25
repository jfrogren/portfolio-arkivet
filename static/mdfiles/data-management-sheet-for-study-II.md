# Data Management Sheet for Study II

## 2020-10-01: OJ finalized his categorization of open question answers
* [Här](/pdfs/201001-OJs-categorization-of-open-question-answers.pdf) är OJs kategoriseringar

## 2020-10-22: JF finalized his categorization of open question answers
* [Här](/htmlfiles/201011-JFs-categorization-of-open-question-answers) är mina kategoriseringar

## 2020-10-22: MK finalized her categorization of open question answers
* [Här](/pdfs/201122-MKs-categorization-of-open-question-answers.pdf) är MKs kategoriseringar

## 2020-11-06: Online meeting with OJ and MK to agree on categorization of open question answers

[Här](/pdfs/201106-Agreed-upon-categorization-of-open-question-answers.pdf) är dokumentationen av våra slutgiltiga kategoriseringar. Det som anges först (på den plats där INTNR är listade) är JF:s svar markerade med ett J, det som anges därefter är MK:s eller OJ:s, markerade med M eller O. Det som anges sist, efter bindestrecket, är det som vi gemensamt kom överens om att svaret skulle kategoriseras som.

## 2020-11-24: UserAge Panelstudy, meeting on data cleaning
Attending: BS, MK & SS

Against the background of the discovery of data quality problems and lack of documentation of data cleaning procedures by Sifo/Kantar a meeting was held to review the issues and set up a process for a final cleaning of the data sets.

Some recurrent patterns had been detected in the data. Though each item in multiple choice questions should always be coded Yes or No, in a substantial number of cases only positive answers were recorded. It was decided that if this was done a consistent manner, the missing responses could be replaced by No. In case there was a mix, some Yes, some No and some missing, it was decided to not to replace missing answers with No as the respondent intention was not clear. Steve will write a syntax to execute the replacement of missing values with No codes. The syntax will be applied to all multiple choice questions (1, 3, 4, 9, 10, 12, 13, 16?). The syntax will be validated by test running and review of output files.

If all options for question 3 are answered No, question 4 should be answered, otherwise the respondent should skip question 4. It was decided Steve will check if this is consistently coded in the database.

Question 7 is a filter question: if answer is Yes or Maybe, questions 8-10 should be answered, if answer No, questions 8-10 should be skipped. It was decided that if questions 8-10 were entirely skipped, but answer for question 7 missing, it could be replaced by No. If questions 8-10 were answered, but 7 missing, it was decided it could be replaced by Yes/Maybe after manual check.

For questions where a response option leads to question of specification, it was decided missing values could be replaced by valid response if a specifying text was provided. This applies to questions 3, 4, 8g, 9, 10, 12, 13, 14, 18, 22. 

Missing values in all other instances (not mentioned above) should remain as missing values. It was decided however, that “system missing” should be replaced by missing code 99 (and recorded as missing code in SPSS, so it is not included in calculations).

Additionally, it was discovered during the meeting that the numbering of some questions in the data set did not match the numbering on the questionnaire. This concerned:

* Question 15 in the database matched 17 in questionnaire
* Question 16 in the database matched 15 in questionnaire
* Question 17 in the database matched 16 in questionnaire
* Question 19 in the database matched 21 in questionnaire
* Question 20 in the database matched 19 in questionnaire
* Question 21 in the database matched 20 in questionnaire

Notes by BS, 2020-11-25


## 2021-01-12: Erhöll uppdaterad fil där missing data kodats om
SS förklarade att filen finns i min mapp i LUSEC under namnet *Target group 1 recoded missing 2021-01-12* och vi gick igenom filen tilsammans.

## 2021-01-15 - 2021-02-03: Omkodning av fritextsvaren i befintliga eller nyskapade kategorier

Skapade en ny fil i LUSEC som jag döpte till *Target group 1 recoded open questions 2021-01-25_Joakim.sav* där jag alltså i de befintliga kolumner som fanns från SS:s omkodningar av missing fyllde i de omkodningar som MK, OJ och jag beslutat oss för när det gällde fritextsvaren.

Insåg också att jag i [denna fil](/pdfs/201106-Agreed-upon-categorization-of-open-question-answers.pdf) endast listat de INTNR och kodningar där OJ,MK och jag var oense och inte omkodningarna för de INTNR där vi initialt var överens. Har slarvat lite i dokumentationen där, men i följande [fil](/htmlfiles/201011-JFs-categorization-of-open-question-answers) har jag listat mina initiala kategoriseringar och baserat på dem går det att räkna ut för vilka INTNR som OJ,MK och jag kategoriserat lika (och inte bara olika).

Det var ju också så att vi kom överens om att #npc skulle ersättas med #nv rakt igenom för att inte komplicera saker i onödan.

### Question 1: Har du som privatperson tidigare deltagit i forskning?
För Fråga 1-alternativen fanns redan _recode_-varianter så jag ändrade i dessa befintliga och skapade inga nya kopior. Här nedan beskrivs vilka omkodningar som gjordes.


#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat fritextsvaren olika initialt, vid efterföljande diskussion kommit överens om: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q1_6_recode i de fall där de inte redan var kategoriserade som '2'.

* 369 - #nv
* 615 - #nv
* 674 - #nv
* 712 - #nv
* 759 - #nv
* 775 - #nv
* 818 - #nv
* 851 - #nv


##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q1_6_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

* 19 - 1.4
* 27 - 1.4
* 149 - 1.4
* 195 - 1.4
* 295 - 1.4
* 375 - 1.4
* 149 - 1.1 + 1.2 + 1.3 + 1.4 + 1.5 


#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q1_6_recode i de fall där de inte redan var kategoriserade som '2'.

+ 66 
+ 68
+ 131 
+ 198 
+ 293 
+ 465
+ 477 
+ 545 
+ 607
+ 701
+ 729 
+ 739 
+ 761 
+ 808 
+ 512


##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q1_6_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 64 - 1.1
+ 136 - 1.5
+ 190 - 1.1 + 1.3
+ 220 - 1.2
+ 239 - 1.5
+ 349 - 1.2
+ 364 - 1.3 + 1.5
+ 490 - 1.2
+ 599 - 1.1 
+ 721 - 1.4
+ 738 - 1.4
+ 777 - 1.1
+ 830 - 1.3

### Question 3: Har du som privatperson tidigare medverkat aktivt i själva genomförandet av forskning?

Skapade en ny kolumn:

* Q3._Other_recode till höger om Q3._Other_.

För de övriga Fråga 3-alternativen fanns redan _recode_-varianter så jag ändrade i dessa befintliga och skapade inga nya kopior. Här nedan beskrivs vilka omkodningar som gjordes.

#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat fritextsvaren olika initialt, vid efterföljande diskussion kommit överens om: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q3_7_recode i de fall där de inte redan var kategoriserade som '2'.

* 68 
* 76 
* 239
* 261
* 278 
* 324 
* 326
* 477
* 484 
* 539
* 550
* 739
* 775
* 853


#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt: 


##### Not valid answers
Omkodningar gjordes enligt följande: #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q3_7_recode i de fall där de inte redan var kategoriserade som '2'.

* 6 
* 34
* 99
* 193 
* 244
* 280
* 356
* 518
* 545
* 576
* 591
* 604
* 650
* 658
* 671
* 709


##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q3_7_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 617 - 3.1

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q3_7_recode och under variabeln Q3_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

1 = Övrigt

* 555 - #pc ("Jag har en forskarbakgrund och har som privatperson och i andra professionalla rollen medverkat i forskningsprocesser") - Övrigt

### Question 4: Om du tidigare inte har medverkat aktivt i forskning, vilken var anledningen?
Skapade en ny kolumn:
* Q4._Other_recode till höger om Q4._Other_.

För de övriga Fråga 4-alternativen fanns redan _recode_-varianter så jag ändrade i dessa befintliga och skapade inga nya kopior. Här nedan beskrivs vilka omkodningar som gjordes.

#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat fritextsvaren olika initialt, vid efterföljande diskussion kommit överens om: 

##### Not valid answers (#nv)
Omkodningar gjordes enligt följande: #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q4_12_recode i de fall där de inte redan var kategoriserade som '2'.

+ 53 
+ 105
+ 129
+ 131
+ 184
+ 209
+ 289
+ 313
+ 357
+ 478
+ 857

##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q4_12_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 58 - 4.11
+ 292 - 4.1
+ 399 - 4.11
+ 488 - 4.1
+ 600 - 4.1 
+ 691 - 4.7 
+ 859 - 4.7


#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt: 

##### Not valid answers
Omkodningar gjordes enligt följande: #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q4_12_recode i de fall där de inte redan var kategoriserade som '2'.

+ 293
+ 516
+ 644
+ 733


##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q4_12_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 31 - 4.11
+ 149 - 4.8
+ 220 - 4.1
+ 300 - 4.1
+ 377 - 4.11
+ 400 - 4.12
+ 404 - 4.12
+ 528 - 4.1 
+ 564 - 4.11
+ 734 - 4.1
+ 779 - 4.7
+ 825 - 4.1


##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q4_12_recode och under variabeln Q4_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Övrigt

+ 370 -("Inte utbildad i forskning") - #pc Övrigt
+ 864 - ("Tveksamt om privatpersoner ska agera aktivt. Forskningens objektivitet mycket viktig.") - #pc Övrigt

### Question 8a-g: Om du fick möjlighet, hur sannolikt är det att du skulle vilja medverka genom att…
Skapade två nya kolumner:
* Q8g_DK_recode till höger om Q8g_DK
* Q8g_recode (för fritextsvaren) till höger om Q8g

Upptäckte dock att vi har missat att kategorisera ett antal fritextsvar. De flesta var sådana som svarat 'Nej', 'Vet inte' eller 'Inget' (eller något motsvarande) och som jag således i Q8g_recode_ kodade om som '2' istället för '1'. Det var följande INTNR som gjort det: 23; 44; 76; 113; 120; 127; 136; 155; 176; 188; 199; 215; 220; 224; 237; 251; 285; 300; 314; 323; 327; 330; 349; 353; 386; 399; 420; 429; 434; 456; 459; 463; 487; 501; 518; 528; 551; 565; 598; 618; 622; 623; 628; 642; 652; 658; 693; 721; 733; 734; 748; 779; 802; 807; 815; 822; 829; 840; 841; 843; 847; 853; 855; 878.

Det vill säga 64 stycken, vilket är påfallande många. Vet inte hur jag har kunnat missa dem.

Därtill var det ett fåtal ytterliggare fritextsvar som inte kategoriserats, nämligen följande:
* INTNR 46: "Det är väl att man sprider det i sin krets och debatterar privat om olika resultat i sådan forskning."
* INTNR 66: "Svara på enkätfrågor, ge synpunkter på ett frågeformulär."
* INTNR 491: "Sprida kunskap till vänner och bekanta."
* INTNR 739: "Vill vara lite delaktig i forskning".

Här gjorde jag så att jag kategoriserade 46, 491 och 739 som 'Not valid' och 66 som 8d ["ge synpunkter på ett frågeformulär"] + den nyskapade kategorin 'Medverkan som försöksperson eller respondent'.


#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat dem olika initialt kommit överens om: 


##### Not valid answers
Omkodningar gjordes enligt följande: #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q8g_DK_recode i de fall där de inte redan var kategoriserade som '2':

* 6 - #nv
* 102 - #nv
* 103 - #nv
* 107 - #nv
* 184 - #nv
* 196 - #nv
* 358 - #nv
* 390 - #nv
* 414 - #nv
* 423 - #nv
* 430 - #nv
* 503 - #nv
* 507 - #nv
* 514 - #nv
* 538 - #nv
* 555 - #nv
* 575 - #nv
* 580 - #nv 
* 613 - #nv
* 624 - #nv
* 670 - #nv
* 861 - #nv

##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q8g_DK_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

* 46 – 8e
* 48 – 8b
* 143 – 8d
* 235 – 8e
* 253 - 8c
* 296 – 8a
* 491 – 8e
* 520 – 8e
* 562 – 8e

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q8g_DK_recode och under variabeln Q8g_recode fylldes 'Medverkan som försöksperson eller respondent' i istället för det befintliga fritextsvaret.

Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q8g_DK_recode och under variabeln Q8g_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Medverkan som försöksperson eller respondent

* 11 (‘Fysisk undersökning’) - #pc Medverkan som försöksperson eller respondent
* 53 (‘Genom enkäter, helst via internet’) - #pc medverkan som försöksperson/respondent
* 99 (‘Enkäter, provtagningar eller tester’) - #pc medverkan som försöksperson/respondent
* 111 (‘Delta i utvärderingar i första hand via internet’) - #pc medverkan som försöksperson/respondent
* 281 (‘Genom enkätundersökning’) - #pc medverkan som försöksperson/respondent
* 490 (‘medverka genom att besvara frågor och genom min egen erfarenhet’) - #pc medverkan som försöksperson/respondent
* 558 (‘sms, mail’) - #pc medverkan som försöksperson/respondent
* 602 ('att bli intervjuad i dessa frågorna') - #pc medverkan som försöksperson/respondent
* 625 (‘svara på frågor’) - #pc medverkan som försöksperson/respondent
* 705 (‘Jag har inga problem att svara på enkäter samt lämna uppgifter om mig själv till forskningen. Jag har alltid godkänt att sjukvården får använda resultat samt prover från mig i forskningssyfte. Jag anser att patienterna ska vara mycket mer delaktiga i sin behandling om dom vill men det är väldigt svårt att få vara det. för er information har jag haft cancer två gånger, oberoende av varandra. Jag har gått på kontroller i 16 år. Jag har varit med att starta en cancerpatientförening (Sarcomföreningen’) och suttit i dess styrelse de två första åren.’)  - #pc medverkan som försöksperson/respondent
* 712 (‘om det är samtal’) - #pc medverkan som försöksperson/respondent
* 740 (‘Ge skriftliga synpunkter’) - #pc medverkan som försöksperson/respondent
* 772 (‘Fysiska tester’) - #pc medverkan som försöksperson/respondent
* 809 (‘Testa nya behandlingsformer’) - #pc medverkan som försöksperson/respondent


#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt: 

Beslutet som MK, OJ och jag gjorde att skapa en ny kategori med namnet "medverkan som försöksperson/respondent" påverkade även retroaktivt de kategoriseringar vi gjort enskilt och där vi då varit överens om att ett svar var "Not valid" om det omfattade en icke aktiv medverkan. Jag gjorde därför om dessa uppenbara svar på en medverkan i forskning som inte var aktiv och kategoriserade dem som tillhörande vår nyskapade kategori.

##### Not valid answers (#nv)
Omkodningar gjordes enligt följande: #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q8g_DK_recode i de fall där de inte redan var kategoriserade som '2':

  + 13 - #nv
  + 17 - #nv
  + 124 - #nv
  + 144 - #nv
  + 148 - #nv
  + 180 - #nv
  + 292 - #nv
  * 409 - #nv
  + 448 - #nv
  + 460 - #nv
  + 478 - #nv
  + 494 - #nv
  + 604 - #nv
  * 709 - #nv 
  + 738 - #nv
  + 751 - #nv
  + 765 - #nv
  + 832 - #nv
  + 866 - #nv
  + 880 - #nv
  
##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q8g_DK_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

  + 60 - 8c
  * 190 - 8c + 8d
  * 250 - 8e
  * 259 - 8e
  + 265 - 8e
  * 321 - 8b
  + 326 - 8c
  + 350 - 8e
  * 360 - 8a
  * 402 - 8e
  + 439 - 8a
  + 443 - 8a 
  + 560 - 8a
  * 578 - 8a
  + 600 - 8a
  * 699 - 8e
  + 725 - 8a
  * 735 - 8b
  * 775 - 8a
  + 864 - 8b
  * 875 - 8e
  
##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier 
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q8g_DK_recode och under variabeln Q8g_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Medverkan som försöksperson eller respondent


  + 3 ('Fylla i frågeformulär') - #pc medverkan som försöksperson/respondent
  + 28  ('Kan svara på enkäter och telefonfrågor') - #pc medverkan som försöksperson/respondent
  + 30 ('Endast svara på enkäter') - #pc medverkan som försöksperson/respondent
  * 35 ('T.ex. vara med och ge synpunkter på medicin/infusion som jag själv använder') - #pc medverkan som försöksperson/respondent
  + 41 ('svara på enkäter som nu') - #pc medverkan som försöksperson/respondent
  * 83 ('Frågor till mig om hur jag som äldre mår och hur jag lever') - #pc medverkan som försöksperson/respondent
  + 118 ('Är med på att testa min kropp') - #pc medverkan som försöksperson/respondent
  + 128 ('försökskanin') - #pc medverkan som försöksperson/respondent
  + 153 ('Svara på enkäter eller telefonintervju, t.ex.') - #pc medverkan som försöksperson/respondent
  + 198 ('T.ex. delta i liknande intervjuer som den här') - #pc medverkan som försöksperson/respondent
  + 203 ('Jag kan tänka mig lämna prover i forskningssyfte') - #pc medverkan som försöksperson/respondent
  + 232 ('Svara på enkät') - #pc medverkan som försöksperson/respondent
  + 268 ('prova nya mediciner') - #pc medverkan som försöksperson/respondent
  + 267 ('Genom att tala om hur jag mår') - #pc medverkan som försöksperson/respondent
  + 347 ('Svar på frågor - enkäter')  - #pc medverkan som försöksperson/respondent
  + 370 ('Skulle kuna tänka sig att vara försöksperson') - #pc medverkan som försöksperson/respondent
  * 416 ('Ja genom telefonintervjuer och enkäter') - #pc medverkan som försöksperson/respondent
  + 422 ('Skulle kunna tänka mig att testa nya mediciner') - #pc medverkan som försöksperson/respondent
  + 432 ('Svara på enkäter, delta i kroppsliga undersökningar') - #pc medverkan som försöksperson/respondent
  + 511 ('Ställa upp som försöksperson') - #pc medverkan som försöksperson/respondent
  + 544 ('Att själv delta som "forskningsobjekt") - #pc medverkan som försöksperson/respondent
  + 545 ('Vill vara en helt vanlig person i projektet "försöksperson" (ej involverad i själva forskargruppen)') - #pc medverkan som försöksperson/respondent
  + 586 ('Besvara enkäter') - #pc medverkan som försöksperson/respondent
  + 590 ('Skulle kunna tänka mig att vara föremål för själva forskningen, som "försökskanin') - #pc medverkan som försöksperson/respondent
  + 614 ('Kan tänka sig t.ex. medicinsk forskning att delta i. Bra att se egna resultat samt vara till hjälp för andra i framtiden.') - #pc medverkan som försöksperson/respondent
  + 636 ('Svara på enkät/frågor för något forskningsprojekt') - #pc medverkan som försöksperson/respondent
  + 650 ('I princip svarar jag gärna på enkätfrågor när det gäller åldrande och hälsa. Svarar på enkät är ok men att rekrytera och så kan vara för mycket för en privatperson') - #pc medverkan som försöksperson/respondent
  + 689 ('Intervju, provtagning') - #pc medverkan som försöksperson/respondent
  + 697 ('Som försöksperson') - #pc medverkan som försöksperson/respondent
  + 804 ('skulle kunna svara på frågor') - #pc medverkan som försöksperson/respondent
  * 833 ('hjälpa till med att svara på frågor') - #pc medverkan som försöksperson/respondent



### Question 9: Via vilka kanaler föredrar du att bli informerad om möjligheter att medverka aktivt i forskning om åldrande och hälsa?

Skapade en ny kolumn:

* Q9._Other_recode till höger om Q9._Other_.

För de övriga Fråga 9-alternativen fanns redan _recode_-varianter så jag ändrade i dessa befintliga och skapade inga nya kopior. Här nedan beskrivs vilka omkodningar som gjordes.


#### OJs förslag på gruppering av kategorier
OJ föreslog att kategorierna kunde grupperas enligt följande:

##### Personal communication
* 9.1 Utskick med brev (Personal communication)
* 9.4 Personligt telefonsamtal, möte (Personal communication)
* 9.5 E-post (Personal communication)
* 9.6 SMS (Personal communication)

##### Mass media
* 9.2 Annons eller artikel i tidning (mass media)
* 9.3 Internet/sociala medier (mass media)
* 9.7 Tv/radio (mass media)
* 9.9 Annons på anslagstavla (mass media)

##### Public event
* 9.8 Offentligt möte, konferens eller föreläsning (Public event)

Detta kan göras med utgångspunkt i det befintliga datasetet men det är ingen prioritet att göra det just nu som jag ser det.


#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat fritextsvaren olika initialt, vid efterföljande diskussion kommit överens om: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q9_10_recode i de fall där de inte redan var kategoriserade som '2'.

* 181 - #nv
* 723 - #nv

##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q9_10_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

* 330 – 9.9
* 402 – 9.4
* 555 – 9.4
* 775 – 9.8

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q9_10_recode och under variabeln Q9_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Övrigt

[Inga INTNR här] 


#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt:

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q9_10_recode i de fall där de inte redan var kategoriserade som '2'.

+ 280 - #nv
+ 456 - #nv
+ 806* - #nv [= redan markerad som '99']
+ 825 - #nv
+ 853 ('via vänner ochh bekanta')#pc - är egentligen svar på nästa fråga, alltså #nv

##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q9_10_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 136 - 9.4 
+ 184 - 9.4 
+ 220 - 9.7
+ 320 - 9.4
+ 390 - 9.4
+ 414 - 9.4 
+ 641 - 9.1 

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier 
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q9_10_recode och under variabeln Q9_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Övrigt

+ 590 - ('Jag vill ha information som är väldigt riktad till mig som individ och inte till för stora grupper') #pc - Övrigt 
+ 733 ('Uppsökande verksamhet') #pc - Övrigt
 



### Question 10: Av vem/vilka föredrar du att få information om möjligheter att medverka aktivt i forskning om åldrande och hälsa, som privatperson?
Skapade en ny kolumn:

* Q10._Other_recode till höger om Q10._Other_.

För de övriga Fråga 10-alternativen fanns redan _recode_-varianter så jag ändrade i dessa befintliga och skapade inga nya kopior. Här nedan beskrivs vilka omkodningar som gjordes.


#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat fritextsvaren olika initialt, vid efterföljande diskussion kom överens om: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q10_9_recode i de fall där de inte redan var kategoriserade som '2'.

* 113 - #nv
* 538 - #nv
* 555 - #nv
* 757 - #nv
* 785 - #nv
* 825 - #nv


##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q10_9_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

* 162 – 10.1
* 181 – 10.1
* 602 – 10.8 (lägg till kollegor till nästa enkät!)

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q9_10_recode och under variabeln Q10_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Övrigt

[Inga INTNR här] 


#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt:

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q10_9_recode i de fall där de inte redan var kategoriserade som '2'.

+ 280 - #nv
+ 286 - #nv 
+ 356 - #nv 
+ 368 - #nv 
+ 459 - #nv
+ 525 - #nv
+ 774 - #nv 

##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q10_9_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 220 - 10.2
+ 323 - 10.2
+ 467 - 10.2
+ 590 - 10.5


##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier 
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q10_9_recode och under variabeln Q10_Other_recode fylldes 'Övrigt' i istället för det befintliga fritextsvaret.

+ 60 ('...från olika myndigheter') #pc 'Övrigt'

<!-- ---

### Q11
* Ingenting att kommentera här. I de fall där värde saknas är det 'Missing value', i övriga fall de alternativ som har angetts.

--->

### Question 12: Vad skulle kunna motivera dig att medverka aktivt i forskning om åldrande och hälsa?

Skapade en ny kolumn:

* Q12._Other_recode till höger om Q12._Other_.

För de övriga Fråga 12-alternativen fanns redan _recode_-varianter så jag ändrade i dessa befintliga och skapade inga nya kopior. Här nedan beskrivs vilka omkodningar som gjordes.

OBS! Insåg att det var väldigt många (uppskattningsvis 150-200) som angett '1' på fråga 12_12 trots att det inte angetts något fritextsvar. Oklart varför. Bestämde mig därför att koda om alla 1:or till 2:or förutom i de fall där valida fritextsvar angetts, alltså sådana svar som kunnat kodats om till någon av fritextkategorierna nedan. 


#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat dem olika initialt kommit överens om överens: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q12_12_recode i de fall där de inte redan var kategoriserade som '2'.

* 733 (‘För att jag själv är i den målgruppen’) - #nv
* 781 (‘Att det sker i —kommun’) - #nv

##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q12_12_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

* 64 (‘Att andra äldre, som kommer efter mig kan få hjälp/förbättringar genom de rön forskningen kommer fram till’) – 12.9 + 12.4
* 321 (‘Om jag blev kontaktad så skulle jag vara motiverad’) – 12.2
* 459 (‘Intresse för ämnet. Jag vill få mer kunskap i ämnet’) – 12.11 (lägg till viktigt+intressant i nästa enkät + lägg till att lära sig något nytt)

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q12_9_recode och under variabeln Q12_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = The conviction that the involvement enriches the research
* 2 = That I trust the researchers and the research
* 3 = The conviction that I can get a better health through involvement
* 4 = Financial compensation
* 5 = The conviction that it really leads to change

* 155 (‘Att jag själv skulle ha personlig nytta av forskningsresultatet och att andra också skulle få nytta av det’) – 12.4 (+ #pc egennytta)* 

*Kommentar: Det är oklart vad som åsyftas med "personlig nytta" i detta fall. Mot bakgrund av att det blir mycket tolkning har jag valt att endast koda om denna till 12.4. och ej skapa en ny kategori som heter 'Egennytta'.

#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q12_12_recode i de fall där de inte redan var kategoriserade som '2'.

+ 327 - #nv

##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q12_12_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 20 - 12.9
+ 60 - 12.11 
+ 136 - 12.4
+ 220 - 12.3 + 12.4
+ 452 - 12.9
+ 775 - 12.11

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q12_12_recode och under variabeln Q12_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = The conviction that the involvement enriches the research
* 2 = That I trust the researchers and the research
* 3 = The conviction that I can get a better health through involvement
* 4 = Financial compensation
* 5 = The conviction that it really leads to change


###### Ny kategori: 1. The conviction that the involvement enriches the research
+ 6 ('Viktigt att man ser människan i forskningen och lyssnar på människan') #pc - Sharing common values (Gemensam värdegrund - Personcentrering vilar på personfilosofins tankar kring vad det innebär att vara en människa)

###### Ny kategori: 2. That I trust the researchers and the research
+ 323 ('Att få veta vad forskningen kommer att leda till i framtiden för mina barn och barnbarn. Att jag känner att jag litar på forskarna skulle motivera mig att delta') - 12.10 + #pc - Sharing common values (Gemensam värdegrund - känsla av tillit)
+ 339 ('Att få känna mig trygg') #pc - Sharing common values (Gemensam värdegrund - känsla av trygghet)
+ 375 ('Att jag får förtroende för forskare') #pc - YES! Sharing common values (Gemensam värdegrund - känsla av förtroende)
+ 538 ('Om jag blev kontaktad av rätt personer som jag känner förtroende för') #pc - Sharing common values (Gemensam värdegrund - känsla av förtroende)
+ 779 ('Om jag fick en seriös förfrågan, beroende på vem som ställer frågan. Om det är en seriös aktör så är jag intresserad') #pc - Sharing common values (Gemensam värdegrund - känsla av tillit) AND #pc: Att någon frågade

###### Ny kategori: 3. The conviction that I can get a better health through involvement
+ 130 ('för att må bättre') #pc - Egennytta (with subcategories see above)
+ 520 - 12.4 + #pc - Egennytta
+ 590 ('Om jag själv skulle kunna få en bättre hälsa av att delta') #pc - Egennytta

###### Ny kategori: 4. Financial compensation
+ 161 ('Få ekonomisk ersättning') #pc - att jag får ekonomisk ersättning (subkategori till egennytta)
+ 185 ('Ekonomisk ersättning kan motivera många') #pc - att jag får ekonomisk ersättnin (subkategori till egennytta)
+ 367 ('ersättning') #pc  - att jag får ekonomisk ersättning
+ 448 ('Ekonomisk ersättning vore bra') #pc - att jag får ekonomisk ersättning (subkategori till egennytta)
+ 810 ('Professionell nivå på forskningen med lämplig ersättning') #pc - Sharing common values (Gemensam värdegrund - känsla av tillit) AND #pc: att jag får ekonomisk ersättning (subkategori till egennytta)

###### Ny kategori: 5. The conviction that it really leads to change
+ 634 ('Politiker tar del av forskningen och använder sig av den i praktiken') #pc - Att det verkligen leder till förändring!
+ 818 ('Forskning som verkligen kan göra skillnad. Bli mer involverad, inte bara informerad') #pc - Att det verkligen leder till förändring!

---

### Q13: Vad skulle du uppleva som hinder för att medverka aktivt i forskning om åldrande och hälsa?
Skapade en ny kolumn:

* Q13._Other_recode till höger om Q13._Other_.

För de övriga Fråga 13-alternativen fanns redan _recode_-varianter så jag ändrade i dessa befintliga och skapade inga nya kopior. Här nedan beskrivs vilka omkodningar som gjordes.

#### De omkodningar som vi (MK, OJ och jag) efter att ha kategoriserat dem olika initialt därefter kommit överens om: 

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q13_10_recode i de fall där de inte redan var kategoriserade som '2'.

[inget]


##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q13_10_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

* 58 (‘Jag upplever att jag är för gammal’) - 13.7 + 13.8 (slå ihop 13.7 + 13.8?)
* 64 – 13.1 + 13.3
* 82 – 13.7
* 124 - 13.7 + 13.8
* 129 – 13.1
* 210 – 13.4
* 252 – 13.1 + 13.2 + 13.3
* 378 – 13.7 + 13.8
* 387 – 13.7 + 13.8
* 448 – 13.4
* 452 – 13.7 + 13.8
* 471 – 13.7 + 13.8
* 521 – 13.7 + 13.8
* 538 – 13.7 + 13.8
* 564 – 13.7 + 13.8
* 590 – 13.6
* 606 – 13.6 + 13.7
* 674 – 13.7 + 13.8
* 738 – 13.7 + 13.8
* 764 – 13.7 + 13.8
* 783 – 13.3
* 791 ('Jag har det bra som det är och har inte tid, då skulle min vardag ändras och det vill jag ej') – 13.6 (lägg eventuellt till brist på intresse till nästa gång).

##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q13_10_recode och under variabeln Q13_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Not thinking to have the experience required
* 2 = Physical distance to research site 
* 3 = Lack of interest in the subject
* 4 = Lack of relevance
* 5 = Not receiving sufficient financial compensation
* 6 = I don't know
* 7 = Lack of trust and/or respect
* 8 = Issues of the protection of privacy
* 9 = There are no obstacles
* 10 = Independence of research can be threatened

[inga INTNR]

#### De omkodningar som vi (MK, OJ och jag) kategoriserat lika initialt:

##### Not valid answers
Omkodningar gjordes enligt följande. #nv motsvarar här '2' och följande INTNR kodades alltså om till '2' i Q13_10_recode i de fall där de inte redan var kategoriserade som '2'.

+ 137 - #nv
+ 669 - #nv


##### Svar som klassades som tillhörande redan befintliga kategorier
Följande INTNR kodades om till att variabeln Q13_10_recode för dem markerades med '2' + att en etta ('1') fylldes i för de befintliga kategorierna som fritextsvaren motsvarade (i de fall där det inte redan var en etta).

+ 53 - 13.8 
+ 96 - 13.8
+ 99 - 13.7
+ 331 - 13.7
+ 408 - 13.7
+ 785 - 13.3 + 13.4


##### Svar som ansågs giltiga och inte tillhörande befintliga kategorier
Följande INTNR erhöll eller fick behålla en etta ('1') för variabeln Q13_10_recode och under variabeln Q13_Other_recode fylldes en siffra för aktuell kategori i istället för det befintliga fritextsvaret enligt följande:

* 1 = Not thinking to have the experience required
* 2 = Physical distance to research site 
* 3 = Lack of interest in the subject
* 4 = Lack of relevance
* 5 = Not receiving sufficient financial compensation
* 6 = I don't know
* 7 = Lack of trust and/or respect
* 8 = Issues of the protection of privacy
* 9 = There are no obstacles
* 10 = Independence of research can be threatened

###### Ny kategori: 1. Not thinking to have the experience required
+ 20 ('Det skulle vara att ämnet ligger oerhört långt från mig, men det är bara ett antagande') #pc - Att jag inte tror att jag har de erfarenheter som efterfrågas
+ 367 ('Upplägg och omfattning. Vet inget om ämnet') #pc - Att jag inte tror att jag har de erfarenheter som efterfrågas

######  Ny kategori: 2. Physical distance to research site 
+ 35 ('Fysiskt avstånd') #pc - Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)
+ 175 ('Är ofta utomlands') #pc - Physical distance to research site (Svårigheter att infinna mig om forskningen genomförs på en viss plats)
+ 266 ('om jag måste åka till annan ort som jag inte känner mig bekväm med') #pc - Physical distance to research site (Svårigheter att infinna mig om forskningen genomförs på en viss plats)
+ 519 ('Avstånd') #pc - Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)
+ 605 ('Kommunikationen att ta sig till möten') #pc - Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)
+ 775 ('Ser inget hinder egentligen, gäller ju plats och tidpunkt') - #pc - Inget hindrar mig idag! + Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)

###### Ny kategori: 3. Lack of interest in the subject
+ 49 ('Ämne som inte intresserar mig') #pc - Brist på intresse för ämnet
+ 60 ('Eventuell brist på intresse för det aktuella ämnet') #pc - Brist på intresse för ämnet
+ 117 ('Eventuellt brist på intresse') #pc - Brist på intresse för ämnet
+ 225 ('Ovilja att vara med helt enkelt') #pc - Brist på intresse för ämnet
+ 234 ('Vill inte hålla på med stillasittande administration') #pc - Brist på intresse för ämnet
+ 297 ('jag är inte motiverad') #pc - #pc - Brist på intresse för ämnet
+ 317 ('om de inte skulle intressera mig, ett smalt ämne där jag ej har intresse exempelvis') #pc - Brist på intresse för ämnet
+ 336 ('Ointresse') #pc - Brist på intresse för ämnet
+ 341 ('jag är inte intresserad') #pc - Brist på intresse för ämnet
+ 423 ('Ej intresserad') #pc - Brist på intresse för ämnet
+ 462 ('Jag är inte intresserad') #pc - Brist på intresse för ämnet
+ 482 ('Vill ej vara med') #pc - Brist på intresse för ämnet
+ 508 ('Forskningens fokus, vilka frågor som utforskas') #pc - Brist på intresse för ämnet
+ 546 ('Inte motiverad') #pc - Brist på intresse/motivation för ämnet
+ 577 ('Vill inte') #pc - Brist på intresse för ämnet
+ 581 ('Inget egentligt intresse') #pc - Brist på intresse/motivation för ämnet
+ 698 ('Brist på intresse') #pc - Brist på intresse för ämnet
+ 725 ('Måttligt intresserad') #pc - Brist på intresse för ämnet
+ 779 ('Om det inte är tillräckligt intressant då ä det ett hinder för mig') #pc - Brist på intresse för ämnet
+ 861 ('Är det inte intressant vill jag ej vara med') #pc - Brist på intresse för ämnet

###### Ny kategori: 4. Lack of relevance
+ 267 ('Jag tycker jag kanske inte kan se relevansen i vissa saker, att jag inte förstår riktigt varför man ska forska om just det') #pc - Brist på relevans – det kommer verkligen inte att göra någon skillnad
+ 314 ('Att forskningsområdet inte känns viktigt') #pc - Brist på relevans – det kommer verkligen inte att göra någon skillnad
+ 316 ('Dålig inriktning, onödigt forskningsmål') #pc - Brist på relevans – det kommer verkligen inte att göra någon skillnad
+ 379 ('Projekt som jag inte anser meningsfulla') #pc - Brist på relevans – det kommer verkligen inte att göra någon skillnad
+ 409 ('Om man uppfattar det som otydlig och dålig kvalitet på forskningen kan det vara ett hinder för mig att delta aktivt i den') #pc - Brist på relevans – det kommer verkligen inte att göra någon skillnad

###### Ny kategori: 5. Not receiving sufficient financial compensation
+ 292 ('Om det skulle kosta mig rent ekonomiskt') #pc - Ingen ekonomisk
ersättning.
+ 411 ('Kostnader för att delta') #pc - Ingen ekonomisk ersättning
+ 781 ('Ingen bil. Får inte kosta pengar, typ tågbiljett') #pc - Ingen ekonomisk ersättning

###### Ny kategori: 6. I don't know
+ 315 ('Tycker både ja och nej delvis på alla frågor. För många och för lika alternativ.') #pc - I don't know
+ 392 ('Svårt att välja svar') #pc - I don’t know
+ 445 ('Kan inte svara på denna fråga') #pc - I don’t know
+ 576 ('Vet ej') #pc - I don’t know
+ 696 ('vet ej') #pc - I don’t know

###### Ny kategori: 7. Lack of trust and/or respect
+ 323 ('Att jag inte skulle känna tillit till forskarna skulle vara ett hinder att delta') #pc - Brist på gemensam värdegrund - avsaknad av tillit
+ 375 ('Att jag får förtroende för forskarna och att dom lyssnar på oss som deltar och medborgarna gör dom ej det vill jag inte vara med') #pc - Brist på gemensam värdegrund - avsaknad av tillit

###### Ny kategori: 8. Issues of the protection of privacy
+ 402 ('Integritetsskyddet') #pc - Issues of the protection of 

###### Ny kategori: 9. There are no obstacles
+ 430 ('inget') #pc - Inget hindrar mig idag!
+ 522 ('ser inget hinder att deltaga') #pc - Inget hindrar mig idag!
+ 765 ('Ingenting specifikt skulle hindra mig från att deltaga') #pc - Inget hindrar mig idag!
+ 775 ('Ser inget hinder egentligen, gäller ju plats och tidpunkt') - #pc - Inget hindrar mig idag! + Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)
+ 810 ('Beredd att medverka som testperson av utveckling med datastyrda hjälpmedel') #pc - Inget hindrar mig idag!

###### Ny kategori: 10. Independence of research can be threatened
+ 864 ('Min uppfattning att forskningens integritet kan rubbas') #pc - Forskningens oberoende kan hotas
  
---

## 2021-02-03: Återstående omkodning av fritextsvar som kvarstår
Fritextsvaren för följande frågor återstår att koda om. Detta avvaktar jag tills vidare med då det inte är så angeläget för den studie jag nu håller på med.

### Q14
Ingenting att kommentera här. Alternativen är '1' och '2' och vissa är missing. 

### Q14_Open
Här behöver alternativen kategoriseras om vi är intresserade av vilka organisationer de är med i. Detta gör jag inte nu.

### Q15.1-5
* Varför kommer inte denna fråga efter fråga 14 i formuläret? Vad var tanken med i vilken följd frågorna kommer?
* När det kommer till 'annat område' var man intresserad av vilket område?
* Inget konstigt i datan: '1', '2' eller missing
* Frågan om datan där inget alternativ är angett på 15.1-5 ska tolkas som 'Missing' eller som 'Nej' återstår att besluta om.

### Q16
Inget att kommentera här heller.

### Q17
Inget att kommentera här heller.  
  
### Q18
Inget att kommentera här heller.

### Q18_Other

* INTNR:
  + 54 ('Jobbar i min skog och fastighet')
  + 62 ('Arbetar och pensionär')
  + 148 ('Pensionär samt hemarbetare inom trädgården då vi har stort hus samt trädgård')
  + 190 ('timanställd ssk i vård')
  + 193 ('håller på att skriva en bok med anledning av tidigare forskningsområdet')
  + 250 ('Ingår i en grupp som har studerar')
  + 253 ('stöd till anhörig 35 år som haft cancer och som får urusel hjälp av AF')
  + 275 ('Arbetar 1-2 dag/vecka + pensionär')
  + 290 ('Bokning av [ohörbart] föreningslokal, trapphusvärd')
  + 296 ('Sjukersättning')
  + 349 ('Pensionär, arbetar på timme inom apoteksutbildning')
  + 351 ('Jobbar lite i egen firma')
  + 379 ('pensionär och förvärvsarbetar 6 timmar/dag')
  + 439 ('Arbetar 30%')
  + 496 ('Familjerådgivare inom Malmöstad, extra arbete')
  + 522 ('deltidsarbetande pensionär')
  + 597 ('Författare')
  + 657 ('"Sjukpensionär"')
  + 741 ('Aktivitetsstöd')
  + 760 ('Bussförare och pastor')
  + 877 ('Volontärarbeten ca 20h/vecka')

### Q19 
* Varför ligger frågan ej i ordningsföljd?
* Inget att kommentera i övrigt

### Q19_Others

<!--

Vilken är din högsta utbildning?

Svarsalternativen är här:

+ 1. Grundskola (folkskola/flickskola/realskola)
+ 2. Gymnasium (folkhögskola)
+ 3. Eftergymnasial utbildning, mindre än tre år (yrkeshögskola/kvalificerad yrkesutbildning)
+ 4. Eftergymnasial utbildning, tre år eller mer
+ 5. Forskarutbildning☐Annat/vill ej uppge

Orkar inte hålla på att dividera med MK och OJ här utan jag gör bedömningarna och omkodningarna själv på eget bevåg

-->

* INTNR:
  + 25 ('Även olika utbildningar inom polisyrket') - har redan svarat '3'
  + 74 ('högskolestudier mindre än 3 år') - 19.4
  + 113 ('Arbetsmiljöutbildning'...) - 6 - #pc 'Övrigt'
  + 139 ('Folkskola') - 19.1
  + 190 ('viss forskarutbildning inom humaniora C- och D-kurser') - 19.5
  + 212 ('barnskötarutbildning') - 19.2
  + 223 ('Yrkesskola 3,5 år i Tyskland') - 19.3
  + 227 ('Livets hårda skola') - har redan svarat '1'
  + 238 ('Yrkesskola metall + Js1 och Js2') - 19.3
  + 305 ('Sjömansexamen i England') - 19.3
  + 306 ('Engelsk Sjömansexamen') - 19.3
  + 327 ('Legitimerad psykolog. Utbildning till psykoterapeut') - 19.4
  + 349 ('Kurs för sysselsättningshandledare') - 6 - #pc 'Övrigt'
  + 369 ('Läkarutbildning') - 19.4
  + 375 ('Folkskola samt realskola samt privat special kurser inom staten och mitt arbete inom kriminalvården') - 6 - #pc 'Övrigt'
  + 379 ('Folkskola + yrkesskola') - 19.3
  + 407 ('Seminarium före högskolan, förskolärarutbildning') - 19.3
  + 419 ('Diverse fackliga kurser') - har redan svarat '3'
  + 465 ('Barnskötare') - 19.2
  + 512 ('hemteknisk yrkesskola') - 19.3
  + 559 ('Kontorsutbildning') - 6 - #pc 'Övrigt'
  + 646 ('Vägmästareutbildning') (=Jägmastarutbildning?i) - 19.4
  + 674 ('Fortbildning på arbetet på onkologen') - 6 - #pc 'Övrigt'
  + 675 ('Datakurs i AMS regi 3 mån') - har redan svarat '3'
  + 740 ('Småskollärarrutbildning') - 6 - #pc 'Övrigt'
  + 781 ('Callcenterutbildning, datakörkort') - har redan svarat '2'
  + 848 ('Undersköterska') - 19.3
  + 854 ('1 termin högskola, kurser') - 19.3
  + 860 ('Hushållsskola, hemvårdarinne-skola') - Har redan svarat '1'
 
 
### Q20 
Inget att kommentera 
  
### Q21 
Inget att kommentera 

### Q22
Inget att kommentera 

### Q22b
* Här behöver det göras en data cleaning av språken, men detta är ej viktigt för min studie så det avvaktar jag med.

### Q23-27
Inget att kommentera

### Q28 
Många 'missing' som är oklart om de motsvarar '2' eller 'Missing'. Kanske inte spelar så stor roll dock. Här räcker det nog att räkna '1':or.


## 2021-02-22: Created new file and translated variables

Today I created  anew file called "Target group 1 recoded open questions 2021-02-22" and in this file I translated all the dependent and independent vriables that I will be using. 
