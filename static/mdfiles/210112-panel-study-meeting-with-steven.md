# 210112: Panel study meeting with Steven
  
Detta möte syftade främst till att Steven skulle presentera den nya uppdaterade filen i vilken data (i viss mån) att städats. Den nya filen återfinns nu i LUSEC i min mapp under tillägget 2021.

Under mötet gick vi också igenom en del frågor kring hur *attitudes* och *awareness* samt willingness kunde kopplas till enkätfrågorna. Vi gick även igenom vilka variabler som var relevanta att ta med.

## Vad vi har bestämt sedan tidigare: Study purpose and RQs

Kort repetition bara av vad som beslutats kring syftets och forskningsfrågornas formulering. Så här lyder de nu:


> The overarching aim was to investigate the awareness and attitudes towards public involvement in research on ageing and health among 60+ citizens in Sweden. 

> One specific aim was to report descriptive results regarding awareness and attitudes. Focusing on willingness to be actively involved in research on ageing and health, another specific aim was to investigate its relationship with demographics and health.

> The analysis for the second specific aim was guided by the following research question: How do the willingness of 60+ citizens to be actively involved in research on ageing and health relate to sex, age, economic situation, level of education and perceived health?


## På vilket sätt har datafilen städats och vad återstår att göra för mig?

När det kommer till 'missing data' som utgjorde den kanske största frågan i data cleaning så hade Steven, Björn, Maya och Oskar efter samråd med SIFO kommit fram till följande:

- If someone answered 'yes' to a multiple-statement question (but not 'no' anywhere in the delfrågor), recode 'missing' as 'no'.
- If someone answered 'yes' and 'no' in a multistatement question, keep missing as missing.

Detta finns också dokumenterat i följande dokument:

<!--
UserAge Panelstudy, meeting on data cleaning, 24/11 2020

Attending:
   Björn Slaug
   Maya Kylén
   Steve Schmidt

Against the background of the discovery of data quality problems and lack of documentation of data cleaning procedures by Sifo/Kantar a meeting was held to review the issues and set up a process for a final cleaning of the data sets.
Some recurrent patterns had been detected in the data. Though each item in multiple choice questions should always be coded Yes or No, in a substantial number of cases only positive answers were recorded. It was decided that if this was done a consistent manner, the missing responses could be replaced by No. In case there was a mix, some Yes, some No and some missing, it was decided to not to replace missing answers with No as the respondent intention was not clear. Steve will write a syntax to execute the replacement of missing values with No codes. The syntax will be applied to all multiple choice questions (1, 3, 4, 9, 10, 12, 13, 16?). The syntax will be validated by test running and review of output files.

If all options for question 3 are answered No, question 4 should be answered, otherwise the respondent should skip question 4. It was decided Steve will check if this is consistently coded in the database.
Question 7 is a filter question: if answer is Yes or Maybe, questions 8-10 should be answered, if answer No, questions 8-10 should be skipped. It was decided that if questions 8-10 were entirely skipped, but answer for question 7 missing, it could be replaced by No. If questions 8-10 were answered, but 7 missing, it was decided it could be replaced by Yes/Maybe after manual check.
For questions where a response option leads to question of specification, it was decided missing values could be replaced by valid response if a specifying text was provided. This applies to questions 3, 4, 8g, 9, 10, 12, 13, 14, 18, 22. 
Missing values in all other instances (not mentioned above) should remain as missing values. It was decided however, that “system missing” should be replaced by missing code 99 (and recorded as missing code in SPSS, so it is not included in calculations).
Additionally, it was discovered during the meeting that the numbering of some questions in the data set did not match the numbering on the questionnaire. This concerned:
Question 15 in the database matched 17 in questionnaire
Question 16 in the database matched 15 in questionnaire
Question 17 in the database matched 16 in questionnaire
Question 19 in the database matched 21 in questionnaire
Question 20 in the database matched 19 in questionnaire
Question 21 in the database matched 20 in questionnaire
Notes by Björn, 2020-11-25

-->

This recoding for missing has already been done by Steven in this updated file that he presented to me today. 

Det som återstår är att jag behöver koda om fritextsvaren på det sätt som Maya, Oskar och jag kom överens om i början av november. Här informerade Steven om att jag ska göra det i form av att lägga till en kolumn intill den befintliga som heter något i stil med *Question_5A_recode*. Steven poängterade att jag bör göra det först och främst för de frågor jag har tänkt använda i artikeln.

## Dokumentera datahanteringen 

Steven rekommenderade mig att skapa ett dokument som heter 'Data management' i vilket jag dokumenterade allt som gjorts med datafilen och att dokumentera i det alla beslut som fattas och när de fattas. Där kan till exempel en rubrik vara 'Question 15 recode'. Detta kan förvaras i LUSEC eller i LU Box.

## Logistic regression related to 'willingness'

Here Steven sayd I should use Odds' Ratio (OR) and the confidence interval. If a value is 0.9 - 1.2 it is not significant. If a confidence interval is 0.7-0.9 or 1.2-1.5 it is significant. Det får alltså inte vara ett interval som inkluderar 1.0 så som jag förstått det.

## Variables to include or exclude

### Perceived health
Here Steven recommended me to keep the four categories and not just speak of 'bad' vs. 'good' health, which Camilla has done (but she also had a much smaller sample.)


### Retired/Working, etc.
Steven recommended me to exclude this variable in this manuscript.

### Economical situation
Steven recommended me to exclude this variable in this manuscript.

### Birthplace
Steven recommended me to exclude this variable in this manuscript.

### Informal carers
Steven recommended me to exclude this variable in this manuscript

### Single household
Steven recommended me to exclude single household

### Politically active
   Steven here suggested: Maybe here make a variable to include either political engagement or interest organisation.


### Which are the questions relating to awareness and attitudes?

#### Awareness

Här kom Steven och jag fram till att *Awareness* motsvarar Question 2. "Känner du till att du som privatperson kan medverka aktivt i själva genomförandet av forskning? (Ja/Nej/Tveksam)"

##### Hur 'awareness' ska presenteras i resultatet
Steven tyckte att detta i resultatet bör ge "one or more sentences" + 1 paragraph in discussion


#### How to handle missing data related to question 2 in the survey?
Denna fråga har inte recodats av Steven så om data är missing för datasetet i denna fråga så är den missing.


#### Attitudes 

Här kom Steven och jag fram till att *Attitudes* motsvarar Question 5a-i (...handlar om din syn på att privatpersoner medverkar aktivt i forskning om åldrande och hälsa. I vilken grad stämmer följande påståenden överens med din uppfattning?)(Stämmer inte alls/Stämmer inte/Stämmer ganska bra/Stämmer precis)

##### How to handle missing data related to question 5a-i in the survey?
Denna fråga har inte recodats av Steven så om data är missing för datasetet i denna fråga så är den missing.

##### Hur 'attitudes' ska presenteras i resultatet
Presented as a figure, tyckte Steven

#### Willingness

Här kom vi fram till att *Willingness* motsvarar Question 7: "Skulle du kunna tänka dig att medverka aktivt i forskning om åldrande och hälsa? (Ja/Nej/Vet ej)"

##### How to handle missing data related to question 7 in the survey?
Denna fråga har inte recodats av Steven så om data är missing för datasetet i denna fråga så är den missing.

##### Hur 'attitudes' ska presenteras i resultatet

Genom en binary logistic regression. För att göra en sådan behöver jag först recode 'maybe' as 'yes'.

Sedan skapa en tabell i stil med den som Camilla har gjort i sin studie, dvs med titel "Participants characteristics and associatons with willingness to participate in research", och kolumnerna: Total - Interest in ... OR (95)% och under 'Interest in' delar jag in det i de två kolumnerna 'Yes/Maybe (%)' och  'No(%)'.' Och raderna har ungefär följande begrepp: Age; Gender; Health; Interest in active involvement; Education. Och det hela avslutas med '* valid percent', vilket betyder att siffrorna baseras påde personer som svarade (och inte på totalt antal som svarade på enkäten.


##### How to handle missing data related to question 5a-i in the survey?
18 is missing according to Steven here.Minns inte om han sa att de recodats men det märker jag ju när jag öppnar datasetet.
