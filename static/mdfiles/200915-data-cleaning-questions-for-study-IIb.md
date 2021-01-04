## Data cleaning questions for study II 
Here are notes related to the data set for the questions in the survey: 
<!--
### Weight
* What does 'Weight' mean here?

*If there is not enough participants in a certain group...to be national representative you have to give certain participants a stronger vote and others a lighter weight* 

*Some analyses you can't weight*
*Weight mostly used for epidemiological reasons.*
*Weight will change each individual's score a bit*

### CHANNEL
* What does channel 1, 2 and 3 mean? I understand that they refer to the medium through which the interview was made but what number means what medium?

1. Computer-assisted web interview
2. Computer-assisted telephon interview
3. Postal

### LK
* What does 'LK' mean?
* INTNR 206 has no value in LK. What does that mean?

*LänKommun - there is a whole list of numbers. If we want to recode to rural and urban. We do not have postal codes. What we can do is compare 'storstadregioner' and rural regions on a broad level. Maybe 'distance to a university' could be used as a measure. Probably not relevant for my paper*
-->

### Gender
* In six cases (INTNR 206; 556; 580; 642; 687; 693) gender is missing. How to deal with that?

*Steven: Talk with Maya to see if she discussed with KANTAR/SIFO. If she doesn't have leave it as missing. If it is a RQ relevant to this, leave out those participants, if not: include it*

### Age
* In six cases (INTNR 206; 556; 580; 642; 687; 693) is missing. How to deal with that?

*Steven: Talk with Maya to see if she discussed with KANTAR/SIFO. If she doesn't have leave it as missing. If it is a RQ relevant to this, leave out those participants, if not: include it*

---

### Q1: Har du som privatperson tidigare deltagit i forskning?
#### Givna svarsalternativ:
* 1.1 Svarat på en enkät
* 1.2 Testat ett nytt läkemedel, behandlingsmetod, tjänst eller produkt
* 1.3 Lämnat prover
* 1.4 Blivit undersökt, testad eller observerad
* 1.5 Blivit intervjuad enskilt eller i grupp
* 1.6 På annat sätt, nämligen...

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 1.1-5
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
   - YES! - Mark with the suggested new category name.
   - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
   - YES!- Mark with '#pc' (=potential category)
   - NO! - Mark with '#npc' (=not potential category)

#### Open question answers
* INTNR: 
  + 19 ('Minne och fysisk förmåga')
  + 27 ('Jag deltog i ett test av EKG då jag skulle sitta på ett speciellt sätt och trampa. Läkarna skulle utvärdera när jag satt på det speciella sättet.')
  + 64 (Tre-delad undersökning, under tre år genom frågeformulär)
  + 66 ('Deltagit i en testperiod på Karolinska om coala, kvinnors [ohörbart] hälsa')
  + 68 ('Prostatacancer')
  + 131 ('Varit med i forskningsprojekt om cancer')
  + 136 ('scapis är ett forskningsprojekt har blivit intervjuad')
  + 149 ('Magnetröntgen som genomfördes i forskningssyfte som hade med höften att göra. Sjukhuset i Malmö.')
  + 190 ('deltagit i Europaforskningsenkät, lämnat prover till cancerforskning')
  + 195 ('Operation test två olika metoder gällande inkontinens')
  + 198; ('Jag har svarat på frågor över telefon tidigare men minns inte riktigt vad det handlade om')
  + 220 ('Jag deltog i forskning sömnproblem. Vi var en grupp som skulle testa olika saker för att få bättre sömn, som kallt i rummet [...] inte dricka kaffe,osv.')
  + 239 ('Intervjuad')
  + 293 ('Kärnkraftsforskning')
  + 295 ('Svarat på frågor om bröstcancer')
  + 349 ('Blindtest gällande klimakterieläkemedel. Använde en dosa för att flera gånger om dagen mata in svar.')
  + 364 ('intervjuad')
  + 369 ('Forskat själv och haft doktorander')
  + 375 (...via telefon)
  + 465 ('Tvilling') 
  + 477;('Efter att blivit opererad för Spinal Stesos')
  + 490 ('I samband med operation av en höftled provades något nytt dropp där vissa personer fick placebo')
  + 512 ('Gott åldrande i Skåne)
  + 545 ('Har själv forskat') 
  + 599 ('blivit intervjuad via enkät')
  + 607 ('Har deltagit i "Monicaprojektet som handlade om hjärt- och kärlsjukdomar')
  + 615 ('Jag var för länge sedan med som representant för Komunalarbetareförbundet i Forskningsetiska kommittén (för regionsjukhus). Läste då alla handlingarna och var med och diskuterade etikprövningarna där')
  + 674 ('Genom mitt arbete på onkologen i Lund')
  + 701 ('Deltagit i undersökning född 53 och tvilling')
  + 712 ('Huddinge')
  + 721 ('Blivit undersökt')
  + 729 ('Kosten')
  + 738 ('undersökt')
  + 739 ('Pga prostatacancer')
  + 759 ('Uppringning')
  + 761 ('Diabetes 2, MÖS 20-talet')
  + 775 ('Lite egen')
  + 777 ('frågeformulär')
  + 808 ('Deltar i ett projekt HND vid Danderyds sjukhus. Hjärta/Njure/Diabetes')
  + 818 ('Har småforskat litegrann på låg nivå')
  + 830 ('lämnat prover')
  + 851 ('Som undersökare')

---  
  
### Q3: Har du som privatperson tidigare medverkat aktivt i själva genomförandet av forskning?
#### Givna svarsalternativ
* 3.1 Medverkat i ett brukarråd, referensgrupp, styrelse eller liknande
* 3.2 Agerat som rådgivare (t.ex. gett synpunkter på forskning eler frågeformulär)
* 3.3 Hjälpt till vid rekrytering av deltagare
* 3.4 Gjort intervjuer eller mätningar och förmedlat dem för
användning i forskningssyfte
* 3.5 Hjälpt till med tolkning av det forskningsmaterial som tagits fram
* 3.6 Har hjälpt till med att sprida forskningsresultat
* 3.7 På annat sätt, nämligen...

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 3.1-6
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
   - YES! - Mark with the suggested new category name.
   - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
   - YES!- Mark with '#pc' (=potential category)
   - NO! - Mark with '#npc' (=not potential category)

#### Open question answers
* INTNR: 
  + 6 ('Om jag anser det relevant kan jag göra det')
  + 34 ('Genom att donera pengar till forskning')
  + 68 ('Utvärdering av prostatacancer') 
  + 76 ('Högt blodtryck Sahlgrenska')
  + 99 ('Genom bl.a. tester av blodcirkulationen efter en operation')
  + 193 ('Har tidigare varit professor i limnologi...')'
  + 239 ('När jag själv har skrivit uppsats')
  + 244 ('Jag har en inopererad datachip i bröstkorgen som registrerar hur hjärtat arbetar. Datan sänds en gång per dygn till hjärtforskare') 
  + 261 ('Genom fd anhörig som är professor i medicin. Konversationer') 
  + 278 ('Sprida information om saker han har läst om när det kommer till olika läkemedel bland sina vänner och bekanta')
  + 280 ('Svarat på frågor inom hemtjänsten') 
  + 324 ('Deltagit i en undersökning om diabetes. Fick svara å frågor om "insulinkänsla, "hyper-nånting" att man somnar. Bedrevs av högskola via vårdcentralen. Genomfördes av husläkaren.')
  + 326 ('Intervjuare. Forskningsstation Mösseberg och Sifo')
  + 337 ('Provat läkemedel')
  + 356 ('Studien, där enläkare ställde frågor och sen fick han ett preparat han skulle använda (som han inte vetvad det var eller om det var placebo) för diabetes') 
  + 477 ('Opinionsundersökningar')
  + 484 ('Studiesamordnare') 
  + 518 ('Svarat på frågor')
  + 539 ('Deltagit i forskning som handlade om sömn och delat upplevelser i grupp') 
  + 545 ('Svarat ja på alla frågor inom yrket. Forskare') 
  + 550 ('Inventerat flyttning till USA i östra Blekinge för lic. avhandling 1959')
  + 555 ('Jag har en forskarbakgrund och har som privatperson och i andra professionalla rollen medverkat i forskningsprocesser')
  + 576 ('Lämnat prov')
  + 591 ('IP har betalt för forskning')
  + 604 ('Muntligt till vänner')
  + 617 ('Adviser board i Lundbecks läkemedel') 
  + 650 ('Biopsi som du gav till en hudläkare')
  + 658 ('Svarade på enkät. Kommer inte ihåg vad det gällde. Troligen hälsa.')
  + 671 ('Svarat på telefonintervjuer')
  + 709 ('Svarade på enkät')
  + 739 ('För långe sedan, hållbarhet och sådan inom träindustrin')
  + 775 ('Lite eget')
  + 853 ('en rapport och föreläsningar') 
  
---

### Q4: Om du tidigare inte har medverkat aktivt i forskning, vilken var anledningen?
#### Givna svarsalternativ
* 4.1 Ingen har frågat eller bett mig
* 4.2 Jag tycker att forskning är svårt/jag förstår inte
* 4.3 Jag är rädd att min anonymitet och integritet inte ska respekteras
* 4.4 Jag har inte tid
* 4.5 Jag orkar inte/det är för krävande
* 4.6 Jag vågar inte
* 4.7 Jag är inte intresserad
* 4.8 Jag tror inte att jag skulle ha något att bidra med
* 4.9 Jag tycker att det är meningslöst
* 4.10 Forskare lyssnar ändå inte
* 4.11 På grund av min sjukdom, funktionsnedsättning eller situation
* 4.12 Annat, nämligen...

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 4.1-11
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
   - YES! - Mark with the suggested new category name.
   - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
   - YES!- Mark with '#pc' (=potential category)
   - NO! - Mark with '#npc' (=not potential category)

#### Open question answers
* INTNR: 
  + 31 ('Sämre hälsa, hög ålder')
  + 53 ('Inte varit med i någon form av forskning tidigare') 
  + 58 ('Jag upplever att jag är för gammal för det')
  + 105 ('har medverkat i studier om forskning')
  + 129 ('Fick information om en möjlighet att delta i forskning men det blev aldrig av.')
  + 131 ('Har deltagit i forskning')
  + 149 ('Jag har inte tyckt att jag har något att tillföra')
  + 184 ('Hjärtforskning har jag deltagit i via blodprover')
  + 209 ('Inte varit aktuellt')
  + 220 ('Jag har inte blivit tillfrågad. Jag tycker att det är ett hinder att sjukvården har en negativ syn på mina hälsoproblem')
  + 289 ('har deltagit tidigare i hjärtforskning')
  + 292 ('Jag vet inte hur man blir utvald att delta')
  + 293 ('Har deltagit')
  + 300 ('Jag har aldrig fått erbjudandet. Jag saknar kännedom om kanalerna hur jag kan delta i utformandet av forskningsprojekt. Jag känner inte till vad det forskas och vad jag skulle kunna delta i.')
  + 313 ('Har varit med i Doris projektet som är forskningsprojekt angående blodsocker')
  + 357 ('Deltagit')
  + 370 ('Inte utbildad i forskning')
  + 377 ('Tinnitus, koncentrationssvårigheter')
  + 399 ('Jag tycker inte om sjukvården, jag är för känslig')
  + 400 ('Jag har bara tagit prover')
  + 404 ('Jag har inte blivit tillfrågad och har helt enkelt inte tänkt på det')
  + 478 ('mon milieu de travail ne m'a pas donne acces aux pratiques de recherches = Inom ramen för mitt arbete har jag jag inte fått möjlighet att bedriva forskning)
  + 488 ('Jag saknade kännedom om det')
  + 516 ('Varit med i läkemedelsforskning')
  + 528 ('Jag ser inga speciella skäl mer än att ingen har frågat mig') 
  + 564 ('Fått en stroke och har många sjukdomar') 
  + 600 ('Har inte varit insatt')
  + 644 ('Har med via BRÅ')
  + 691 ('Inte intresserad av att fylla i enkäter')
  + 733 ('Jag jobbade på Uppsala universitet, då var jag mer involverad i att förmedla forskning som bedrevs vid Uppsala universitet och riktade mig då främst till lärare.')
  + 734 ('Jag har inte ens tänkt på det, eftersom ingen har frågat mig')
  + 779 ('Jag har inte varit tillräckligt intresserad')
  + 825 ('Om frågan kommer måste jag ju då fundera över om det är intressant för mig eller inte')
  + 857 ('Varit med cia cancer forskning')
  + 859 ('Inte intresserad')
  + 864 ('Tveksam om privatpersoner ska agera aktivt. Forskningens objektivitet mycket viktigt.')

---

### Q8a-g: Om du fick möjlighet, hur sannolikt är det att du skulle vilja medverka genom att…
#### Givna svarsalternativ
* **8a** ...bidra till planering och utformning av forskningsprojekt? T.ex. identifiera forskningsfrågor eller hjälpa till med att ta fram informationsmaterial och frågeformulär.
* **8b** ...ingå i ett i ett brukarråd, referensgrupp, styrelse eller liknande? T.ex. diskutera forskningsaktiviteter eller ge synpunkter på forskningen.
* **8c** ...genomföra uppgifter i forskningsprojekt? T.ex. rekrytera deltagare, genomföra intervjuer.
* **8d** ...analysera det forskningsmaterial som tagits fram? T.ex. hjälpa till med tolkning av resultat.
* **8e** ...sprida forskningsresultat? T.ex. ge synpunkter på texter eller presentera resultat vid offentliga möten.
* **8f** ...bidra till en ansökan om forskningsfinansiering? T.ex. föreslå forskningsfrågor så att de speglar målgruppens behov.
* **8g** ...Finns det något annat sätt du skulle kunna tänka dig att medverka på? (Om ja, vänligen ange hur)

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 8a-g
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
   - YES! - Mark with the suggested new category name.
   - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
   - YES!- Mark with '#pc' (=potential category)
   - NO! - Mark with '#npc' (=not potential category)

#### Open question answers
* INTNR:
  + 3 ('Fylla i frågeformulär') 
  + 6 ('kanske beror på om jag finner det relevant')
  + 11 ('Fysisk undersökning') 
  + 13 ('Tycker det är bra om äldre personer involveras i sådana här forskningsprojekt')
  + 17 ('Delta i forskningsstudien')
  + 28 ('Kan svara på enkäter och telefonfrågor')
  + 30 ('Endast svara på enkäter')
  * 35 ('T.ex. vara med och ge synpunkter på medicin/infusion som jag själv använder') - The forms for such an exchange decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation.
  + 41 ('svara på enkäter som nu')
  * 46 ('det är väl att man sprider det i sin krets och debatterar privat om olika resultat inom sådan forskning')
  * 48 ('(Delta i) diskussionsgrupper') 
  * 53 ('Genom enkäter, helst via internet') - oklart om det åsyftas att svara på eller utforma enkäter
  + 60 ('Jag skulle tänka mig att intervjua') 
  * 83 ('Frågor till mig om hur jag som äldre mår och hur jag lever')
  * 99 ('Enkäter, provtagningar eller tester') - Not clear if the person means participating in creating/giving  or receiving/answering.
  + 102 ('Om jag ser något ämne som är intressant skulle jag kunna tänka mig det')
  + 103 ('Det är väl främst frågor som berör sådant jag själv råkat ut för...')
  + 107 ('Att bidra med egna erfarenheter')
  * 111 ('Delta i utvärderingar i första hand via internet') - The forms for such 'evaluations' decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation.
  + 118 ('Är med på att testa min kropp')
  + 124 ('Har hela mitt liv varit involverad i forskning, verksamhetsutveckling och utbildning och om min, och mina vänners åldrande kan bidraga till en ökad kunskap om åldrandet och hur man kan förbättra livskvaliteten för en allt större grupp individer skulle det kännas mycket motiverande.')
  + 128 ('försökskanin') 
  * 143 ('Komma med synpunkter på de resultaten som publiceras som just handlar om åldrande och hälsa') 
  + 144 ('Jag var en testperson')
  + 148 ('Möjligen om jag blir sjuk och man då använder mina datauppgifter för att hjälpa andra människor')
  + 153 ('Svara på enkäter eller telefonintervju, t.ex.')
  + 180 ('Man ska bidra på de sätten man kan och som man har tid med.')
  + 184 ('Kan om tid finns')
  * 190 ('Kan tänka mig att telefonintervjua, åka runt och intervjua, sammanställa och utvärdera resultat, etc.') 
  * 196 ('Van att läsa långa texter och utredningar och kan bidra med något liknande')
  + 198 ('T.ex. delta i liknande intervjuer som den här')
  + 203 ('Jag kan tänka mig lämna prover i forskningssyfte')
  + 232 ('Svara på enkät')
  + 235 ('gärna genom inlägg på sociala medier som facebook, instagram, twitter'))
  * 250 ('Informera på pensionärsträffar t.ex.')
  * 253 ('skulle kunna fråga en grupp äldre, typ ca 10 pers om aktuella frågor som är intressanta fr målgruppen') 
  * 259 ('Gå på föreläsningar, lyssna online. Prata om de med andra människor')
  + 265 ('Kan tänka sig berätta resultat för sin umgängeskrets.') 
  + 268 ('prova nya mediciner')
  + 267 ('Genom att tala om hur jag mår')
  + 281 ('Genom enkätundersökning')
  + 296 ('Ge synpunkter på ett frågeformulär')
  * 321 ('delta i diskussionsgrupp')
  + 292 ('Nej, det är väl i så fall att bidra med svar på hur man själv mår om forskningen handlar om det man själv drabbats av. Det är erfarenheten som ger kvalitet i de svar man ger.')
  + 326 ('Utföra telefonintervjuer'))
  + 347 ('Svar på frågor - enkäter')
  + 350 ('Sprida information på en arbetsplats')
  + 358 ('engagera en vän')
  * 360 ('Bidra med förslag till forskningsområden')
  + 370 ('Skulle kuna tänka sig att vara försöksperson')
  * 390 ('Genom att driva vissa frågor gällande pensionärer')
  * 402 ('Kommunikationsmässigt, via nät eller media. Eller artiklar i tidningen')
  * 409 ('..måste ha baskunskaper, informera tydligt på vilka premisser...sätta sig in i området'))
  + 414 ('Problem och forskning angående sköldkörteln'))
  * 416 ('Ja genom telefonintervjuer och enkäter') - Unclear if person means conduct these interviews or participate in them
  + 422 ('Skulle kunna tänka mig att testa nya mediciner')
  + 423 ('Troligen mer intresserad att medverka om man har egen eller närstående sjukdom'))
  + 430 ('Egna erfarenheter bl.a.')
  + 432 ('Svara på enkäter, delt ai kroppsliga undersökningar')
  + 439 ('Ge synpunkter på frågeformulär')
  + 443 ('Ge synpunkter på enkätfrågor')
  + 448 ('Problem med att forskning inte tas tillvara på. Det fattas något som förankrar forskningsresultat i verkliga situationer, t.ex. att det är dålig mat på ålderdomshem enligt undersökningar, me att det trots allt fortsätter vara så')
  + 460 ('göra insatser som har med åldrande och hälsa för folk som har problemer')
  + 478 ('la recherche dans tous les domaines est tres importante, il faut la soutenir et l'encourager par tous les moyens possibles. = Forskning inom alla områden är mycket viktigt, det gäller att stödja och uppmuntra den med alla medel som står till buds)
  + 490 ('medverka genom att besvara frågor och genom min egen erfarenhet')
  * 491 ('Sprida kunskap till vänner och bekanta') 
  + 494 ('Åhörare')
  * 503 ('Vill endast deltaga om ersättning utgår')
  + 507 ('Dela med sig av sina erfarenheter')
  + 511 ('Ställa upp som försöksperson') 
  + 514 ('Med min livserfarenhet kan jag nog bidra med')
  * 520 ('Kunna informera i olika typer av grupper, både yngre och äldre, föreningar och andra typer av grupper i hennes närhet') 
  * 538 ('jag skulle kunna tänka mig att vara med i ett grupparbete')
  + 544 ('Att själv delta som "forskningsobjekt")
  + 545 ('Vill vara en helt vanlig person i projektet "försöksperson" (ej involverad i själva forskargruppen)')
  + 555 (= många olika förslag)
  + 558 ('sms, mail')
  + 560 ('Ge synpunkter på frågeformulär')
  * 562 ('Jag skulle kunna sprida information i pensionärsföreningarna') 
  + 575 ('Jobba i olika mindre grupper')
  * 578 ('genom frågeformulär') - oklart om det åsyftas att svara på eller utforma frågeformulär
  + 580 ('Endast i närområdet')
  + 586 ('Besvara enkäter')
  + 590 ('Skulle kunna tänka mig att vara föremål för själva forskningen, som "försökskanin')
  + 600 ('Om man kunde hjälpa forskare i ett tidigt skede innan saker är bestämt. Det är så man skulle kunna påverka.')
  * 602 ('att bli intervjuad i dessa frågorna')
  + 604 ('Hög ålder. Min erfarenhet. Meddela mina egna teorier')
  + 613 ('error')
  + 614 ('Kan tänka sig t.ex. medicinsk forskning att delta i. Bra att se egna resultat samt vara till hjälp för andra i framtiden.')
  * 624 ('dela ut flygblad')
  + 625 ('svara på frågor')
  + 636 ('Svara på enkät/frågor för något forskningsprojekt')
  + 650 ('I princip svarar jag gärna på enkätfrågor när det gäller åldrande och hälsa. Svarar på enkät är ok men att rekrytera och så kan vara för mycket för en privatperson')
  + 670 ('Är receptarie med nästan 50 års apoteksarbete, erfarenhet som först apotekstekniker, sen receptarie och apotekschef, bland annat på ett vårdcentralsapotek där jag jobbade ensam. Har pratat hälsa och läkemedel med människor, gör fortfarande trots att jag är pensionär.')
  + 689 ('Intervju, provtagning') 
  + 697 ('Som försöksperson')
  * 699 ('distribuera information')
  + 705 ('Jag har inga problem att svara på enkäter samt lämna uppgifter om mig själv till forskningen. Jag har alltid godkänt att sjukvården får använda resultat samt prover från mig i forskningssyfte. Jag anser att patienterna ska vara mycket mer delaktiga i sin behandling om dom vill men det är väldigt svårt att få vara det. för er information har jag haft cancer två gånger, oberoende av varandra. Jag har gått på kontroller i 16 år. Jag har varit med att starta en cancerpatientförening (Sarcomföreningen') och suttit i dess styrelse de två första åren.')'
  * 709 ('Berätta om mina erfarenheter med åldrande föräldrar...relaterat till mitt eget åldrande')
  + 712 ('om det är samtal'))
  + 725 ('synpunkter på frågeformulär')
  * 735 ('Ingå i en arbetsgrupp där olika frågor diskuteras') 
  + 738 ('De vill ha en sammanfattning om hur man har haft det, hur man upplevde fallet') 
  + 739 ('Ville vara lite delaktig i forskningen')
  + 740 ('Ge skriftliga synpunkter')
  + 751 ('Egna erfarenheter')
  + 765 ('Det skulle vara om man gjorde saker aktivt när man blev tillfrågad')
  + 772 ('Fysiska tester')
  * 775 ('Inringa forskningsområden')
  + 804 ('skulle kunna svara på frågor')
  + 809 ('Testa nya behandlingsformer')
  + 832 ('Genom egna erfarenheter')
  * 833 ('hjälpa till med att svara på frågor') - The forms for 'answering questions' decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation.
  + 861 ('Ja om det är något jag finner viktigt och angeläget och intresserar mig så kan jag tänka mig hjälpa')
  + 864 ('Viktigt att inte gå in på forskarnas område. Kan bestå med synpunkter på exempelvis frågeformulär, m.m.')
  + 866 ('delta på lämligt sätt')
  * 875 ('Att informera inom PRO eller annan orgnisation') 
  + 880 ('Med synpunkter)

---
  
### Q9: Via vilka kanaler föredrar du att bli informerad om möjligheter att medverka aktivt i forskning om åldrande och hälsa?
#### Givna svarsalternativ
* 9.1 Utskick med brev
* 9.2 Annons eller artikel i tidning
* 9.3 Internet/sociala medier
* 9.4 Personligt telefonsamtal, möte
* 9.5 E-post
* 9.6 SMS
* 9.7 Tv/radio
* 9.8 Offentligt möte, konferens eller föreläsning
* 9.9 Annons på anslagstavla
* 9.10 På annat sätt, nämligen:

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 9.1-9
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
   - YES! - Mark with the suggested new category name.
   - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
   - YES!- Mark with '#pc' (=potential category)
   - NO! - Mark with '#npc' (=not potential category)

#### Open question answers
* INTNR:
  + 136 ('muntligt via sociala nätverk')
  + 181 ('Genom föreningslivet')
  + 184 ('det bästa är via läkare')
  + 220 ('via program som 'Fråga doktorn')
  + 280 ('Inte på något annat sätt')
  + 320 ('Vid läkarbesök')
  + 330 ('Information i hissar')
  + 390 ('Genom personligt besök') 
  + 402 ('Samtalsgrupp t.ex.')
  + 414 ('Genom VC, "min" läkare')
  + 456 ('inget')
  + 555 ('olika mötesplatser')
  + 590 ('Jag vill ha information som är väldigt riktad till mig som individ och inte till för stora grupper')
  + 733 ('Uppsökande verksamhet')
  + 641 ('Jag tror att skickar man ut brev till alla äldre och saker per post..så kommer fler att delta') 
  + 723 ('Att pensionärsorganisationer ger information om att man kan medverka aktivt')
  + 775 ('"webinar"')
  + 806 ('Inte alls')
  + 825 ('Är inte särskilt intresserad vara med denna gången i och med att vi ringde')
  + 853 ('via vänner och bekanta')

---

### Q10: Av vem/vilka föredrar du att få information om möjligheter att medverka aktivt i forskning om åldrande och hälsa, som privatperson?
#### Givna svarsalternativ
* 10.1 Intresseorganisationer
* 10.2 Regional hälso- och sjukvård
* 10.3 Kommunal hälso- och sjukvård eller socialtjänst (t.ex. hemtjänst)
* 10.4 Privat hälso- och sjukvård
* 10.5 Forskare
* 10.6 Företag
* 10.7 Rekryteringsfirma
* 10.8 Familj, vänner eller bekanta
* 10.9 På annat sätt, nämligen:

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 10.1-8
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
  - YES! - Mark with the suggested new category name.
  - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
  - YES!- Mark with '#pc' (=potential category)
  - NO! - Mark with '#npc' (=not potential category)

#### Open question answers
* INTNR:
  + 280 ('Inte (heller) på något annat sätt')
  + 60 ('...från olika myndigheter')
  + 113 ('Där äldre samlas på olika möten, t.ex. på vår [otolkbart] biosalongen eller samlingsal boende')
  + 162 ('Fackföreningar')
  + 181 ('Svarar i föregående fråga')
  + 220 ('Vårdcentralen skulle kunna ha enkäter som man kan fylla i')
  + 286 ('Facebook')
  + 323 ('Det ska vara sjukvårdens forskare som direkt vänder sig till mig för att mina åkommor')
  + 356 ('Informativ sida online')
  + 368 ('Genom telefonsamtal/telefonintervju')
  + 459 ('Via TV-program som TV-doktorn och Fråga doktorn')
  + 467 ('Min läkare')
  + 525 ('vet ej')
  + 538 ('Människor överlag som man kan lita på, som arbetar utan politisk och ekonomisk vinning')
  + 555 ('Beror på frågeställningen och målgrupp')
  + 590 ('...av Universitetet som driver forskningsprojekt') --> Q10e
  + 602 ('genom kollegor')
  + 757 ('Ingen åsikt')
  + 774 ('Via brev')
  + 785 ('Vill helst av allt få information av någon personligen')
  + 825 ('vill inte bli kontaktad alls')  

---

### Q11
* Ingenting att kommentera här. I de fall där värde saknas är det 'Missing value', i övriga fall de alternativ som har angetts.

---

### Q12: Vad skulle kunna motivera dig att medverka aktivt i forskning om åldrande och hälsa?
#### Givna svarsalternativ
* 12.1 Att få förtur till tjänster (t.ex hälso- och sjukvård, social omsorg, service, boende etc)
* 12.2 Att få känna mig betydelsefull
* 12.3 Att få reda på mer om min situation
* 12.4 Att bidra till samhället
* 12.5 Att du inte har något att förlora
* 12.6 Att forskningen bör gå framåt (dvs. någon måste ställa upp)
* 12.7 Att få kontakt med andra i samma situation
* 12.8 Att vara hjälpsam mot forskaren
* 12.9 Att få bättre tjänster, produkter
* 12.10 Att få reda på vad studien kommer att leda till
* 12.11 Att forskningen handlar om något som du tycker är viktigt
* 12.12 Annat, nämligen
* 12.13 Inget, du vill inte medverka aktivt i forskning

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 12.1-13
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
   - YES! - Mark with the suggested new category name.
   - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
   - YES!- Mark with '#pc' (=potential category)
   - NO! - Mark with '#npc' (=not potential category)
#### Open question answers

* INTNR:
  + 6 ('Viktigt att man ser människan i forskningen och lyssnar på människan')
  + 20 ('Att hitta lösningar på problem, som nya hjälpmedel eller ngt som är utformat fel som påverkar åldrande via dålig kvalitet på hjälpmedel som hjälper äldre som har problem med armar och ben..[...]..hemtjänsten gör ju ett jättebra fotarbete men det behövs påfyllning från forskning inte så långa glapp mellan de på golvet och forskningen läkare uppdateras men det ska även undersköterskor och de på golvet också få..är önskvärt')
  + 60 ('Jag är intresserad av ämnet och det motiverar mig')
  + 64 ('Att andra äldre, som kommer efter mig kan få hjälp/förbättringar genom de rön forskningen kommer fram till')
  + 130 ('för att må bättre')
  + 136 ('att man gör något positivt för andra')
  + 155 ('Att jag själv skulle ha personlig nytta av forskningsresultatet och att andra också skulle få nytta av det')
  + 161 ('Få ekonomisk ersättning')
  + 185 ('Ekonomisk ersättning kan motivera många') --- Även dig?
  + 220 ('Att jag själv skulle få hjälp med mina problem. Att jag själv skulle få god kontakt med en forskningsexpert på min hälsa. Jag skulle tänka mig att donera min kropp så att forskarna skulle undersöka min kropp efter min död för att kunna bidra till ett svar på vad det är jag lider av')
  + 321 ('Om jag blev kontaktad så skulle jag vara motiverad')
  + 323 ('Att få veta vad forskningen kommer att leda till i framtiden för mina barn och barnbarn. Att jag känner att jag litar på forskarna skulle motivera mig att delta')
  + 327 ('Brist på tid')
  + 339 ('Att få känna mig trygg')
  + 367 ('ersättning')
  + 375 ('Att jag får förtroende för forskare')
  + 448 ('Ekonomisk ersättning vore bra')
  + 452 ('...om det handlar om sjukvård och mediciner som blir bättre') --> Q12_9
  + 459 ('Intresse för ämnet. Jag vill få mer kunskap i ämnet')
  + 520 ('Samhällsnyttan och för den enskilda individen är viktig')
  + 538 ('Om jag blev kontaktad av rätt personer som jag känner förtroende för')
  + 590 ('Om jag själv skulle kunna få en bättre hälsa av att delta')
  + 634 ('Politiker tar del av forskningen och använder sig av den i praktiken')
  + 733 ('För att jag själv är i den målgruppen')
  + 775 ('viktigt område och behöver belysas')
  + 779 ('Om jag fick en seriös förfrågan, beroende på vem som ställer frågan. Om det är en seriös aktör så är jag intresserad')
  + 781 ('Att det sker i --- kommun')
  + 810 ('Professionell nivå på forskningen med lämplig ersättning')
  + 818 ('Forskning som verkligen kan göra skillnad. Bli mer involverad, inte bara informerad')

---

### Q13: Vad skulle du uppleva som hinder för att medverka aktivt i forskning om åldrande och hälsa?
#### Givna svarsalternativ
* 13.1 Min brist på förståelse för forskning
* 13.2 Svårigheter att förstå de sätt som forskare uttrycker sig på
* 13.3 Forskarnas brist på kompetens vad gäller att engagera privatpersoner
* 13.4 Skillnader i förväntningar mellan forskare och mig själv
* 13.5 Olikheter mellan deltagare
* 13.6 Brist på tid
* 13.7 Alltför krävande för mig
* 13.8 Egen privat situation
* 13.9 Tror inte att det leder till förändringar av min situation
* 13.10 Annat, nämligen

#### Instructions for categorizing open question answers below
1. Does it fit in one (or several) of the given category/ies?
   - YES! recode it to that/those category/ies, e.g. 13.1-9
   - NO! Go to 2.
2. Is it an answer that you consider valid to the question being asked?
   - YES! - Go to 3.
   - NO! - Mark with '#nv' (=not valid) and if you like, write why you consider answer not valid
3. Does the answer correspond to a new category?
   - YES! - Mark with the suggested new category name.
   - NO! - Go to 4.
4. Does the answer have the potential to belong to a new category?
   - YES!- Mark with '#pc' (=potential category)
   - NO! - Mark with '#npc' (=not potential category)

#### Open question answers
* INTNR:
  + 20 ('Det skulle vara att ämnet ligger oerhört långt från mig, men det är bara ett antagande')
  + 35 ('Fysiskt avstånd')
  + 49 ('Ämne som inte intresserar mig')
  + 53 ('Dofter. Min fru har SHR och dofter fastnar i hår och kläder, vilket jag då tar med hem och kan orsaka symptom för henne. KOL har jag själv och därför är dofter inte heller bra för mig.')
  + 58 ('Jag upplever att jag är för gammal')
  + 60 ('Eventuell brist på intresse för det aktuella ämnet')
  + 64 ('Att, såsom varande icke-akademiker, har svårt att förstå vad som förväntas av mig och hur jag kan bidra konstruktivt.')
  + 82 ('Om jag känner att jag nödvändigt måste delta är det ngt annat, men jag är gammal...')
  + 96 ('anhörigvårdare')
  + 99 ('Smärtsamma prover/tester')
  + 117 ('Eventuellt brist på intresse')
  + 124 ('Är idag frisk och vital men om detta förändras negativt är det naturligtvis ett hinder')
  + 129 ('Att man saknar de rätta grundkunskaperna om t.ex. tillvägagångssätt')
  + 137 ('Förbättringar för andra')
  + 175 ('Är ofta utomlands')
  + 210 ('Ett hinder kan vara att personer i fyrtioårsåldern dominerar i samhället')
  + 225 ('Ovilja att vara med helt enkelt')
  + 234 ('Vill inte hålla på med stillasittande administration')
  + 252 ('finns inga hinder förutsatt att jag förstår det jag ska göra')
  + 266 ('om jag måste åka till annan ort som jag inte känner mig bekväm med')
  + 267 ('Jag tycker jag kanske inte kan se relevansen i vissa saker, att jag inte förstår riktigt varför man ska forska om just det')
  + 292 ('Om det skulle kosta mig rent ekonomiskt')
  + 297 ('jag är inte motiverad')
  + 314 ('Att forskningsområdet inte känns viktigt')
  + 315 ('Tycker både ja och nej delvis på alla frågor. För många och för lika alternativ.')
  + 316 ('Dålig inriktning, onödigt forskningsmål')
  + 317 ('om de inte skulle intressera mig, ett smalt ämne där jag ej har intresse exempelvis')
  + 323 ('Att jag inte skulle käna tillit till forskarna skulle vara ett hinder att delta')
  + 331 ('Gammal, borde vara pigare för att orka med')
  + 336 ('Ointresse')
  + 341 ('jag är inte intresserad')
  + 367 ('Upplägg och omfattning. Vet inget om ämnet')
  + 375 ('Att jag får förtroende för forskarna och att dom lyssnar på oss som deltar och medborgarna gör dom ej det vill jag inte vara med')
  + 378 ('min ålder - 97 år')
  + 379 ('Projekt som jag inte anser meningsfulla')
  + 387 ('Min ålder=85 år')
  + 392 ('Svårt att välja svar')
  + 402 ('Integritetsskyddet')
  + 408 ('Hörselnedsättning')
  + 409 ('Om man uppfattar det som otydlig och dålig kvalitet på forskningen kan det vara ett hinder för mig att delta aktivt i den')
  + 411 ('Kostnader för att delta')
  + 423 ('Ej intresserad')
  + 430 ('inget')
  + 445 ('Kan inte svara på denna fråga')
  + 448 ('Känner sig inte som äldre')
  + 452 ('Jag hittar inget hinder, kan delta, men isf skulle det vara sjukdom om jag ej kan')
  + 462 ('Jag är inte intresserad')
  + 471 ('Min höga ålder (92 år)')
  + 482 ('Vill ej vara med')
  + 508 ('Forskningens fokus, vilka frågor som utforskas')
  + 519 ('Avstånd')
  + 521 ('Jag är gammal och har gjort mitt för samhället')
  + 522 ('ser inget hinder att deltaga')
  + 538 ('min ålder i sådana fall, är en gammal gubbe')
  + 546 ('Inte motiverad')
  + 564 ('Hög åldern är en svårighet')
  + 576 ('Vet ej')
  + 577 ('Vill inte')
  + 581 ('Inget egentligt intresse')
  + 590 ('Jag arbetar fortfarande')
  + 605 ('Kommunikationen att ta sig till möten')
  + 606 ('Beroende på omfattning')
  + 669 ('Bra att många ställer upp')
  + 674 ('fysisk handikapp, åldern')
  + 696 ('vet ej')
  + 698 ('Brist på intresse')
  + 725 ('Måttligt intresserad')
  + 738 ('åldersrelaterat och har svårt att medverka på grund av att jag bor långt borta')
  + 764 ('I min ålder blir jag lat och bekväm')
  + 765 ('Ingenting specifikt skulle hindra mig från att deltaga')
  + 775 ('Ser inget hinder egentligen, gäller ju plats och tidpunkt')
  + 779 ('Om det inte är tillräckligt intressant då ä det ett hinder för mig')
  + 781 ('Ingen bil. Får inte kosta pengar, typ tågbiljett')
  + 783 ('Jag vill ha en bred information innan vad forskningen handlar om i detalj och vad den leder till..')
  + 785 ('Forskarna som ofta är för unga för att förstå hur en gammal människa känner')
  + 791 ('Jag har det bra som det är och har inte tid, då skulle min vardag ändras och det vill jag ej')
  + 810 ('Beredd att medverka som testperson av utveckling med datastyrda hjälpmedel')
  + 861 ('Är det inte intressant vill jag ej vara med')
  + 864 ('Min uppfattning att forskningens integritet kan rubbas')


<!--
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
* INTNR:
  + 25 ('Även olika utbildningar inom polisyrket')
  + 74 ('högskolestudier mindre än 3 år')
  + 113 ('Arbetsmiljöutbildning'...)
  + 139 ('Folkskola')
  + 190 ('viss forskarutbildning inom humaniora C- och D-kurser')
  + 212 ('barnskötarutbildning')
  + 223 ('Yrkesskola 3,5 år i Tyskland')
  + 227 ('Livets hårda skola')
  + 238 ('Yrkesskola metall + Js1 och Js2')
  + 305 ('Sjömansexamen i England')
  + 306 ('Engelsk Sjömansexamen')
  + 327 ('Legitimerad psykolog. Utbildning till psykoterapeut')
  + 349 ('Kurs för sysselsättningshandledare')
  + 369 ('Läkarutbildning')
  + 375 ('Folkskola samt realskola samt privat special kurser inom staten och mitt arbete inom kriminalvården')
  + 379 ('Folkskola + yrkesskola')
  + 407 ('Seminarium före högskolan, förskolärarutbildning')
  + 419 ('Diverse fackliga kurser')
  + 465 ('Barnskötare')
  + 512 ('hemteknisk yrkesskola')
  + 559 ('Kontorsutbildning')
  + 646 ('Vägmästareutbildning') (=Jägmastarutbildning?i)
  + 674 ('Fortbildning på arbetet på onkologen')
  + 675 ('Datakurs i AMS regi 3 mån')
  + 740 ('Småskollärarrutbildning')
  + 781 ('Callcenterutbildning, datakörkort')
  + 848 ('Undersköterska')
  + 854 ('1 termin högskola, kurser')
  + 860 ('Hushållsskola, hemvårdarinne-skola')
  
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
-->
