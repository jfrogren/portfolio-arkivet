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

Det som anges först är Joakims svar markerade med ett J: det som anges därefter är Mayas eller Oskars, markerade med M: eller O:



#### Open question answers
* INTNR: 
  + 19 ('Minne och fysisk förmåga') J:#npc M: 1.4 
  + 27 ('Jag deltog i ett test av EKG då jag skulle sitta på ett speciellt sätt och trampa. Läkarna skulle utvärdera när jag satt på det speciella sättet.') J: 1.2 M:1.4 
  + **64 (Tre-delad undersökning, under tre år genom frågeformulär) J:1.1 M:1.1**
  + **66 ('Deltagit i en testperiod på Karolinska om coala, kvinnors [ohörbart] hälsa') J:#npc M:#npc**
  + **68 ('Prostatacancer') J:#npc M#npc**
  + **131 ('Varit med i forskningsprojekt om cancer') J:#npc M:#npc**
  + **136 ('scapis är ett forskningsprojekt har blivit intervjuad') J:1.5 M: 1.5**
  + 149 ('Magnetröntgen som genomfördes i forskningssyfte som hade med höften att göra. Sjukhuset i Malmö.') J:1.2 M:1.4
  + **190 ('deltagit i Europaforskningsenkät, lämnat prover till cancerforskning') J:1.1 + 1.3 M:1.1 + 1.3**
  + 195 ('Operation test två olika metoder gällande inkontinens') J:1.2 M:#npc
  + **198; ('Jag har svarat på frågor över telefon tidigare men minns inte riktigt vad det handlade om') J: #npc -- oklart om enkät eller intervju M:#npc**
  + **220 ('Jag deltog i forskning sömnproblem. Vi var en grupp som skulle testa olika saker för att få bättre sömn, som kallt i rummet [...] inte dricka kaffe,osv.') J:1.2 M:1.2** 
  + **239 ('Intervjuad') J:1.5 M:1.5**
  + **293 ('Kärnkraftsforskning')J:#npc M:#npc**
  + 295 ('Svarat på frågor om bröstcancer') J:#npc - oklart om enkät eller intervju M:1.1 alt. 1.5
  + **349 ('Blindtest gällande klimakterieläkemedel. Använde en dosa för att flera gånger om dagen mata in svar.') J:1.2 M:1.2**
  + **364 ('intervjuad') J:1.5 M:1.5**
  + 369 ('Forskat själv och haft doktorander') J:#nv M:#npc
  + 375 (...via telefon) J:#npc - för lite info M:1.1 alt. 1.5
  + **465 ('Tvilling') J:#npc - för lite info, kolla vad x fyllt i för svar redan M:#npc**
  + **477;('Efter att blivit opererad för Spinal Stesos') J:#npc - oklart vad för slags forskning M:#npc**
  + **490 ('I samband med operation av en höftled provades något nytt dropp där vissa personer fick placebo') J:1.2 M:1.2**
  + 512 ('Gott åldrande i Skåne) J:#npc - för lite info kolla vad x fyllt i för svar redan M:1.1-1.5
  + **545 ('Har själv forskat') J:#nv M:#nv**
  + **599 ('blivit intervjuad via enkät') J:1.1 M:1.1**
  + **607 ('Har deltagit i "Monicaprojektet som handlade om hjärt- och kärlsjukdomar')  J:#npc - för lite info kolla vad x fyllt i för svar redan M:#npc**
  + 615 ('Jag var för länge sedan med som representant för Komunalarbetareförbundet i Forskningsetiska kommittén (för regionsjukhus). Läste då alla handlingarna och var med och diskuterade etikprövningarna där') J:#pc M:#nv
  + 674 ('Genom mitt arbete på onkologen i Lund') J:#npc - för lite info M:#nv
  + **701 ('Deltagit i undersökning född 53 och tvilling') J:#npc - för lite info M:#npc**
  + 712 ('Huddinge') J:#npc - för lite info M:#nv
  + **721 ('Blivit undersökt') J:1.4 M:1.4**
  + **729 ('Kosten') J:#npc - för lite info om vad det rör sig om M:#npc**
  + **738 ('undersökt') J:1.4 M:1.4**
  + **739 ('Pga prostatacancer') J:#npc - för lite info om vad det handlar om M:#npc** 
  + 759 ('Uppringning') J:#npc - för lite info om det handlar om intervju, enkät eller annat M:#nv
  + **761 ('Diabetes 2, MÖS 20-talet') J:#npc - för lite info M:#npc**
  + 775 ('Lite egen') J:#npc - för lite info M:#nv
  + **777 ('frågeformulär') J:1.1 M:1.1**
  + **808 ('Deltar i ett projekt HND vid Danderyds sjukhus. Hjärta/Njure/Diabetes') J:#npc - för lite info M:#npc**
  + 818 ('Har småforskat litegrann på låg nivå') J:#npc - oklart vad det betyder M:#nv
  + **830 ('lämnat prover') J:1.3 M:1.3**
  + 851 ('Som undersökare') J:#npc - för lite info M:#nv

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
  + **6 ('Om jag anser det relevant kan jag göra det') J:#nv M:#nv**
  + **34 ('Genom att donera pengar till forskning') J:#nv M:#nv**
  + 68 ('Utvärdering av prostatacancer') J:#npc - för lite info M:#nv 
  + 76 ('Högt blodtryck Sahlgrenska') J:#npc - för lite info M:#nv
  + **99 ('Genom bl.a. tester av blodcirkulationen efter en operation') J:#nv M:#nv**
  + **193 ('Har tidigare varit professor i limnologi...') J:#nv M:#nv**
  + 239 ('När jag själv har skrivit uppsats') J:#npc - oklart vad det betyder M:#nv
  + **244 ('Jag har en inopererad datachip i bröstkorgen som registrerar hur hjärtat arbetar. Datan sänds en gång per dygn till hjärtforskare') J:#nv M:#nv**
  + 261 ('Genom fd anhörig som är professor i medicin. Konversationer') J:#npc - lite för oklart vad konversationerna syftar till M:#nv
  + 278 ('Sprida information om saker han har läst om när det kommer till olika läkemedel bland sina vänner och bekanta') J:#nv - att sprida info om vad man läst räknas inte som aktiv medverkan här M:#npc
  + **280 ('Svarat på frågor inom hemtjänsten') J:#npc - lite för oklart vad det handlar om för att kunna kategorisera M:#npc**
  + 324 ('Deltagit i en undersökning om diabetes. Fick svara å frågor om "insulinkänsla, "hyper-nånting" att man somnar. Bedrevs av högskola via vårdcentralen. Genomfördes av husläkaren.') - J:#npc - oklart om enkät eller intervju, se hur x svarat M:#nv
  + 326 ('Intervjuare. Forskningsstation Mösseberg och Sifo') J:3.4 M:#nv
  + **337 ('Provat läkemedel') J:#nv M:#nv**
  + **356 ('Studien, där enläkare ställde frågor och sen fick han ett preparat han skulle använda (som han inte vetvad det var eller om det var placebo) för diabetes') J:#nv M:#nv**
  + 477 ('Opinionsundersökningar') J:#npc - oklart vilken roll x hade i detta om x besvarade eller utformade/genomförde M:#nv
  + 484 ('Studiesamordnare') J:#pc N:#nv
  + **518 ('Svarat på frågor') J:#nv - ej aktiv medverkan att bara svara på frågor M:#nv**
  + 539 ('Deltagit i forskning som handlade om sömn och delat upplevelser i grupp') J:#npc - för lit einfo för att ta ställning till om det var aktiv medverkan eller ej M:#nv
  + **545 ('Svarat ja på alla frågor inom yrket. Forskare') J:#nv - det står utryckligen 'som privatperson' i instruktionerna M:#nv** 
  + 550 ('Inventerat flyttning till USA i östra Blekinge för lic. avhandling 1959') J:#npc - oklart vilken roll x hade i denna studie M:#nv
  + 555 ('Jag har en forskarbakgrund och har som privatperson och i andra professionalla rollen medverkat i forskningsprocesser') J:#npc - oklart vilken sorts medverkan M:#nv (Flera här svarar utifrån en profesionell roll, ej som privatperson. Dessa markerar jag som NV.)
  + **576 ('Lämnat prov') J:#nv M:#nv**
  + **591 ('IP har betalt för forskning') J:#nv M:#nv**
  + **604 ('Muntligt till vänner') J:#npc - för lite info för att förstå om det är aktiv medverkan M:#npc**
  + **617 ('Adviser board i Lundbecks läkemedel') J:3.1 M:3.1**
  + **650 ('Biopsi som du gav till en hudläkare') J:#nv M:#nv**
  + **658 ('Svarade på enkät. Kommer inte ihåg vad det gällde. Troligen hälsa.') J:#nv M:#nv**
  + **671 ('Svarat på telefonintervjuer') J:#nv M:#nv**
  + **709 ('Svarade på enkät') J:#nv M:#nv**
  + 739 ('För långe sedan, hållbarhet och sådan inom träindustrin') J:#npc M:#nv
  + 775 ('Lite eget') J:#npc M:#nv
  + 853 ('en rapport och föreläsningar') J:#npc M#nv
  
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
  + **31 ('Sämre hälsa, hög ålder') J:4.11 M:4.11 och #pc pga ålder**
  + 53 ('Inte varit med i någon form av forskning tidigare') J:#pc M:#nv
  + 58 ('Jag upplever att jag är för gammal för det') J:4.11 M:#pc pga ålder
  + 105 ('har medverkat i studier om forskning') J:#npc M:#nv
  + 129 ('Fick information om en möjlighet att delta i forskning men det blev aldrig av.') J:#pc M:#nv
  + 131 ('Har deltagit i forskning') J:#npc M:#nv
  + **149 ('Jag har inte tyckt att jag har något att tillföra') J:4.8 M:4.8** 
  + 184 ('Hjärtforskning har jag deltagit i via blodprover') J:#npc M:#nv 
  + 209 ('Inte varit aktuellt') J:#pc M:#npc
  + **220 ('Jag har inte blivit tillfrågad. Jag tycker att det är ett hinder att sjukvården har en negativ syn på mina hälsoproblem') J:4.1 + #pc M:4.1**
  + 289 ('har deltagit tidigare i hjärtforskning') J:#npc M:#nv
  + 292 ('Jag vet inte hur man blir utvald att delta') J:#pc M:4.1
  + **293 ('Har deltagit') J:#nv M:#nv**
  + **300 ('Jag har aldrig fått erbjudandet. Jag saknar kännedom om kanalerna hur jag kan delta i utformandet av forskningsprojekt. Jag känner inte till vad det forskas och vad jag skulle kunna delta i.') J:4.1 + #pc M:4.1**
  + 313 ('Har varit med i Doris projektet som är forskningsprojekt angående blodsocker') J:#npc M:#nv
  + 357 ('Deltagit') J:#npc M:#nv
  + **370 ('Inte utbildad i forskning') J:#pc M:#pc saknar kunskap om forskning (Tveksam till denna men den skiljer sig från svarsalternativen.)**
  + **377 ('Tinnitus, koncentrationssvårigheter') J:4.11 M:4.11**
  + 399 ('Jag tycker inte om sjukvården, jag är för känslig') J:#pc M:4.11
  + **400 ('Jag har bara tagit prover') J:#nv M:#nv**
  + **404 ('Jag har inte blivit tillfrågad och har helt enkelt inte tänkt på det') J:4.1 M:4.1**
  + 478 ('mon milieu de travail ne m'a pas donne acces aux pratiques de recherches = Inom ramen för mitt arbete har jag jag inte fått möjlighet att bedriva forskning) J:#pc M:#nv
  + 488 ('Jag saknade kännedom om det') J:#pc M:4.1 (Inte klockren, vi får diskutera. )
  + **516 ('Varit med i läkemedelsforskning') J:#nv M:#nv**
  + **528 ('Jag ser inga speciella skäl mer än att ingen har frågat mig') J:4.1 M:4.1**
  + **564 ('Fått en stroke och har många sjukdomar') J:4.11 M:4.11**
  + 600 ('Har inte varit insatt') J:#pc M:4.1 (Inte klockren, vi får diskutera.)
  + **644 ('Har med via BRÅ') J:#nv M:#nv**
  + 691 ('Inte intresserad av att fylla i enkäter') J:#nv M:4.7
  + **733 ('Jag jobbade på Uppsala universitet, då var jag mer involverad i att förmedla forskning som bedrevs vid Uppsala universitet och riktade mig då främst till lärare.') J:#nv M:#nv**
  + **734 ('Jag har inte ens tänkt på det, eftersom ingen har frågat mig') J:4.1 M:4.1**
  + **779 ('Jag har inte varit tillräckligt intresserad') J:4.7 M:4.7**
  + **825 ('Om frågan kommer måste jag ju då fundera över om det är intressant för mig eller inte') J:4.1 M:4.1**
  + 857 ('Varit med cia cancer forskning') J:#npc M:#nv
  + 859 ('Inte intresserad') J:4.7 M:4.1
  + **864 ('Tveksam om privatpersoner ska agera aktivt. Forskningens objektivitet mycket viktigt.') J:#pc M:#pc får fundera på namn**

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

Vissa respondenter har ej förstått att det handlar om aktiv medverkan. Maya föreslår att det skulle kunna vara en ny kategori: Att vilja medverka i forskning men inte aktivt.En annan aspekteller 'take' på detta faktum är att många helt enkelt inte uppfattat vad enkäten egentligen handlar om för slags deltagande. I detta fall gör jag så att jag markerar de svar som enligt Maya inte representerar aktiv medverkan med  "-- ej aktiv medverkan"

#### Open question answers
* INTNR:
  + **3 ('Fylla i frågeformulär') J:#nv M:#nv** -- ej aktiv medverkan
  + 6 ('kanske beror på om jag finner det relevant') J:#pc M:#nv
  + 11 ('Fysisk undersökning') J:#npc M:#nv -- ej aktiv medverkan
  + **13 ('Tycker det är bra om äldre personer involveras i sådana här forskningsprojekt') J:#nv M:#nv**
  + **17 ('Delta i forskningsstudien') J:#nv M:#nv** -- ej aktiv medverkan
  + **28 ('Kan svara på enkäter och telefonfrågor') J:#nv M:#nv** -- ej aktiv medverkan
  + **30 ('Endast svara på enkäter') J:#nv M:#nv** -- ej aktiv medverkan
  * **35 ('T.ex. vara med och ge synpunkter på medicin/infusion som jag själv använder') - J:#nv The forms for such an exchange decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation. M:#nv (tolkningsfråga enl. M)** 
  + **41 ('svara på enkäter som nu') J:#nv M:#nv** -- ej aktiv medverkan
  * 46 ('det är väl att man sprider det i sin krets och debatterar privat om olika resultat inom sådan forskning') J:8e? M:#npc
  * 48 ('(Delta i) diskussionsgrupper') J:8b M:#nv -- ej aktiv medverkan
  * 53 ('Genom enkäter, helst via internet') J:8c? alt. #pc - oklart om det åsyftas att svara på eller utforma enkäter M:#nv -- ej aktiv medverkan
  + **60 ('Jag skulle tänka mig att intervjua') J:8c M:8c**
  * **83 ('Frågor till mig om hur jag som äldre mår och hur jag lever') J:#nv M:#nv** -- ej aktiv medverkan
  * 99 ('Enkäter, provtagningar eller tester') J:#npc - Not clear if the person means participating in creating/giving  or receiving/answering. M:#nv (tolkningsfråga)
  + 102 ('Om jag ser något ämne som är intressant skulle jag kunna tänka mig det') J:#pc N:#nv
  + 103 ('Det är väl främst frågor som berör sådant jag själv råkat ut för...') J:#pc - på denna och föregående svar betonas att det beror på M:#nv 
  + 107 ('Att bidra med egna erfarenheter') J:#npc M:8a + 8b
  * 111 ('Delta i utvärderingar i första hand via internet') J:#npc - The forms for such 'evaluations' decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation. M:#nv -- ej aktiv medverkan
  + **118 ('Är med på att testa min kropp')J:#nv M:#nv** -- ej aktiv medverkan
  + **124 ('Har hela mitt liv varit involverad i forskning, verksamhetsutveckling och utbildning och om min, och mina vänners åldrande kan bidraga till en ökad kunskap om åldrandet och hur man kan förbättra livskvaliteten för en allt större grupp individer skulle det kännas mycket motiverande.') J:#nv M:#nv**
  + **128 ('försökskanin') J:#nv M:#nv** -- ej aktiv medverkan
  * 143 ('Komma med synpunkter på de resultaten som publiceras som just handlar om åldrande och hälsa') J:#nv M:8d (Inte klockrent.)
  + **144 ('Jag var en testperson') J:#nv M:#nv** -- ej aktiv medverkan
  + **148 ('Möjligen om jag blir sjuk och man då använder mina datauppgifter för att hjälpa andra människor') J:#nv M:#nv**
  + **153 ('Svara på enkäter eller telefonintervju, t.ex.') J:#nv M:#nv** -- ej aktiv medverkan
  + **180 ('Man ska bidra på de sätten man kan och som man har tid med.') J:#nv M:#nv**
  + 184 ('Kan om tid finns') J:#pc - återigen det beror på, i detta fall om tid finns M:#nv
  * **190 ('Kan tänka mig att telefonintervjua, åka runt och intervjua, sammanställa och utvärdera resultat, etc.') J:8c + 8d M:8c+8d**
  * 196 ('Van att läsa långa texter och utredningar och kan bidra med något liknande') J:8d? M:8e
  + **198 ('T.ex. delta i liknande intervjuer som den här') J:#nv M:#nv** -- ej aktiv medverkan
  + **203 ('Jag kan tänka mig lämna prover i forskningssyfte') J:#nv M:#nv** -- ej aktiv medverkan
  + **232 ('Svara på enkät') J:#nv M:#nv**-- ej aktiv medverkan
  + 235 ('gärna genom inlägg på sociala medier som facebook, instagram, twitter')) J:#pc M:#npc
  * **250 ('Informera på pensionärsträffar t.ex.') J:8e M:8e**
  * 253 ('skulle kunna fråga en grupp äldre, typ ca 10 pers om aktuella frågor som är intressanta fr målgruppen') J:8c M:#npc
  * **259 ('Gå på föreläsningar, lyssna online. Prata om de med andra människor') J:8e? M:8e (Inte klockren, tolkningsfråga**
  + **265 ('Kan tänka sig berätta resultat för sin umgängeskrets.') J:8e? M:8e (Dock ej offentliga möten, ska nog vara #npc?**
  + **268 ('prova nya mediciner') J:#nv M:#nv** -- ej aktiv medverkan
  + **267 ('Genom att tala om hur jag mår') J:#nv M:#nv** -- ej aktiv medverkan
  + 281 ('Genom enkätundersökning') J:#npc M:#nv -- ej aktiv medverkan
  + 296 ('Ge synpunkter på ett frågeformulär') J:8b M:8a
  * **321 ('delta i diskussionsgrupp') J:8b M:8b**
  + **292 ('Nej, det är väl i så fall att bidra med svar på hur man själv mår om forskningen handlar om det man själv drabbats av. Det är erfarenheten som ger kvalitet i de svar man ger.') J:#nv M:#nv** -- ej aktiv medverkan
  + **326 ('Utföra telefonintervjuer')) J:8c M:8c**
  + **347 ('Svar på frågor - enkäter') J:#nv M:#nv** -- ej aktiv medverkan
  + **350 ('Sprida information på en arbetsplats') J:8e M:8e (Tolkningsfråga)**
  + 358 ('engagera en vän') J:8c? M:#npc
  * **360 ('Bidra med förslag till forskningsområden') J:8a M:8a**
  + **370 ('Skulle kuna tänka sig att vara försöksperson') J:#nv M:#nv** -- ej aktiv medverkan
  * 390 ('Genom att driva vissa frågor gällande pensionärer') J:#pc M:8a (Tolkningsfråga)
  * **402 ('Kommunikationsmässigt, via nät eller media. Eller artiklar i tidningen') J:8e? M:8e (Tolkningsfråga)**
  * **409 ('..måste ha baskunskaper, informera tydligt på vilka premisser...sätta sig in i området')) J:#nv M:#nv**
  + 414 ('Problem och forskning angående sköldkörteln')) J:#npc M:#nv
  * **416 ('Ja genom telefonintervjuer och enkäter') - J:#npc Unclear if person means conduct these interviews or participate in them M:#nv (För lite info för att kunna ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + **422 ('Skulle kunna tänka mig att testa nya mediciner') J:#nv M:#nv** -- ej aktiv medverkan
  + 423 ('Troligen mer intresserad att medverka om man har egen eller närstående sjukdom')) J:#pc - återigen - det beror på ämnet och hur relevant jag anser det vara M:#nv
  + 430 ('Egna erfarenheter bl.a.') J:#npc M:#nv
  + **432 ('Svara på enkäter, delta i kroppsliga undersökningar') J:#nv M:#nv** -- ej aktiv medverkan
  + **439 ('Ge synpunkter på frågeformulär') J:8a 8c? M:8a**
  + **443 ('Ge synpunkter på enkätfrågor') J:8a 8c? M:8a**
  + **448 ('Problem med att forskning inte tas tillvara på. Det fattas något som förankrar forskningsresultat i verkliga situationer, t.ex. att det är dålig mat på ålderdomshem enligt undersökningar, me att det trots allt fortsätter vara så') J:#nv  M:#nv**
  + **460 ('göra insatser som har med åldrande och hälsa för folk som har problemer') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning)))**
  + **478 ('la recherche dans tous les domaines est tres importante, il faut la soutenir et l'encourager par tous les moyens possibles. = Forskning inom alla områden är mycket viktigt, det gäller att stödja och uppmuntra den med alla medel som står till buds) J:#nv M:#nv**
  + 490 ('medverka genom att besvara frågor och genom min egen erfarenhet') J:#npc M:8b (Tolkningsfråga)
  * 491 ('Sprida kunskap till vänner och bekanta') J:8e M:8c (Dock ej offentliga möten, ska nog vara #npc?)
  + **494 ('Åhörare') J:#nv M:#nv**
  * 503 ('Vill endast deltaga om ersättning utgår') J:#pc - återigen - det beror på alltså inte lätt att ge entydigt svar på frågan M:#nv
  + 507 ('Dela med sig av sina erfarenheter') J:#npc M:8b (Tolkningsfråga)
  + **511 ('Ställa upp som försöksperson') J:#nv M:#nv** -- ej aktiv medverkan
  + 514 ('Med min livserfarenhet kan jag nog bidra med') J:#npc M:8b (Tolkningsfråga)
  * 520 ('Kunna informera i olika typer av grupper, både yngre och äldre, föreningar och andra typer av grupper i hennes närhet') J:8e M:8c 
  * 538 ('jag skulle kunna tänka mig att vara med i ett grupparbete') J:#pc - detta kan man ju se som en önskan om att vara med i ett projektinrktat arbete. Något sådant alternativ ges inte nu. M:#npc
  + **544 ('Att själv delta som "forskningsobjekt") J:#nv M:#nv** -- ej aktiv medverkan
  + **545 ('Vill vara en helt vanlig person i projektet "försöksperson" (ej involverad i själva forskargruppen)') J:#nv M:#nv** -- ej aktiv medverkan
  + 555 (= många olika förslag) - kolla upp M:#nv
  + 558 ('sms, mail') J:#npc M:#nv
  + **560 ('Ge synpunkter på frågeformulär') J:8a el. 8c M:8a**
  * 562 ('Jag skulle kunna sprida information i pensionärsföreningarna') J:8e M:8c
  + 575 ('Jobba i olika mindre grupper') J:8b M:#nv (För lite info för att ta ställning) 
  * **578 ('genom frågeformulär') J:#npc - oklart om det åsyftas att svara på eller utforma frågeformulär M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning)**
  + 580 ('Endast i närområdet') J:#pc - återigen inget entydigt svar utan det beror på det specifika projektet M:#nv
  + **586 ('Besvara enkäter') J:#nv M:#nv** -- ej aktiv medverkan
  + **590 ('Skulle kunna tänka mig att vara föremål för själva forskningen, som "försökskanin') J:#nv M:#nv** -- ej aktiv medverkan
  + **600 ('Om man kunde hjälpa forskare i ett tidigt skede innan saker är bestämt. Det är så man skulle kunna påverka.') J:8a M:8a**
  * 602 ('att bli intervjuad i dessa frågorna') J:#npc M:#nv -- ej aktiv medverkan
  + **604 ('Hög ålder. Min erfarenhet. Meddela mina egna teorier') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + 613 ('error') J:#npc M:#nv 
  + **614 ('Kan tänka sig t.ex. medicinsk forskning att delta i. Bra att se egna resultat samt vara till hjälp för andra i framtiden.') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  * 624 ('dela ut flygblad') J:#pc M:8c
  + 625 ('svara på frågor') J:#npc M:#nv -- ej aktiv medverkan
  + **636 ('Svara på enkät/frågor för något forskningsprojekt') J:#nv M:#nv** -- ej aktiv medverkan
  + **650 ('I princip svarar jag gärna på enkätfrågor när det gäller åldrande och hälsa. Svarar på enkät är ok men att rekrytera och så kan vara för mycket för en privatperson') J:#nv M:#nv** -- ej aktiv medverkan
  + 670 ('Är receptarie med nästan 50 års apoteksarbete, erfarenhet som först apotekstekniker, sen receptarie och apotekschef, bland annat på ett vårdcentralsapotek där jag jobbade ensam. Har pratat hälsa och läkemedel med människor, gör fortfarande trots att jag är pensionär.') J:#pc M:#nv
  + **689 ('Intervju, provtagning') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + **697 ('Som försöksperson') J:#nv M:#nv** -- ej aktiv medverkan
  * **699 ('distribuera information') J:8e? #npc M:8c eller 8e**
  + 705 ('Jag har inga problem att svara på enkäter samt lämna uppgifter om mig själv till forskningen. Jag har alltid godkänt att sjukvården får använda resultat samt prover från mig i forskningssyfte. Jag anser att patienterna ska vara mycket mer delaktiga i sin behandling om dom vill men det är väldigt svårt att få vara det. för er information har jag haft cancer två gånger, oberoende av varandra. Jag har gått på kontroller i 16 år. Jag har varit med att starta en cancerpatientförening (Sarcomföreningen') och suttit i dess styrelse de två första åren.')' J:#pc - kan starta patientförening anses vara aktivt deltagande i forskning? M:#nv -- ej aktiv medverkan
  * **709 ('Berätta om mina erfarenheter med åldrande föräldrar...relaterat till mitt eget åldrande') J:#npc el. #nv  - oklart vad berättandet sker i för form el. format vilket är avgörande för om detta ska klassas som aktivt deltagande i forskning M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + 712 ('om det är samtal')) J:#pc - återigen så är det pot M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))
  + **725 ('synpunkter på frågeformulär') J:8a M:8a**
  * **735 ('Ingå i en arbetsgrupp där olika frågor diskuteras') J:8b M:8b**
  + **738 ('De vill ha en sammanfattning om hur man har haft det, hur man upplevde fallet') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + 739 ('Ville vara lite delaktig i forskningen') J:#npc M:#nv
  + 740 ('Ge skriftliga synpunkter') J:#pc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))
  + **751 ('Egna erfarenheter') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + **765 ('Det skulle vara om man gjorde saker aktivt när man blev tillfrågad') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + 772 ('Fysiska tester') J:#npc M:#nv -- ej aktiv medverkan
  * **775 ('Inringa forskningsområden') J:8a M:8a**
  + **804 ('skulle kunna svara på frågor') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + 809 ('Testa nya behandlingsformer') J:#npc M:#nv -- ej aktiv medverkan
  + **832 ('Genom egna erfarenheter') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  * **833 ('hjälpa till med att svara på frågor') J:#npc - The forms for 'answering questions' decides whether it can be called 'active' participation, I suppose. Or maybe it is not under any circumstances 'active' participation. M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  + 861 ('Ja om det är något jag finner viktigt och angeläget och intresserar mig så kan jag tänka mig hjälpa') J:#pc - återigen villkorat baserat på intresse M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))
  + **864 ('Viktigt att inte gå in på forskarnas område. Kan bestå med synpunkter på exempelvis frågeformulär, m.m.') J:8a,8b eller 8c? M:8a**
  + **866 ('delta på lämligt sätt') J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**
  * **875 ('Att informera inom PRO eller annan orgnisation') J:8e M:8e**
  + **880 ('Med synpunkter) J:#npc M:#nv (För lite info för att ta ställning (alltså menar M egentligen #npc enligt min tolkning))**

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
  + **136 ('muntligt via sociala nätverk') J:9.4 + ev. #pc O:9.4**
  + 181 ('Genom föreningslivet') J:#pc O:#npc (a sender that potentially can use all channels) 
  + **184 ('det bästa är via läkare') J:9.4 + #pc O:9.4**
  + **220 ('via program som 'Fråga doktorn') J:9.7 O:9.7**
  + **280 ('Inte på något annat sätt') J:#nv O:#nv**
  + **320 ('Vid läkarbesök') J:9.4 + #pc O:9.4**
  + 330 ('Information i hissar') J:#pc O:9.9
  + **390 ('Genom personligt besök') J:9.4 O:9.4**
  + 402 ('Samtalsgrupp t.ex.') J:#pc O:9.4
  + **414 ('Genom VC, "min" läkare') J:9.4 + ev. #pc O:9.4**
  + **456 ('inget') J:#nv O:#nv**
  + 555 ('olika mötesplatser') J:#npc - för vagt för att förstå O:#9.4
  + **590 ('Jag vill ha information som är väldigt riktad till mig som individ och inte till för stora grupper') J:#pc O:#pc: Personal communication (with the four subcategories 9.1; 9.4; 9.5; 9.6)** 
  + **733 ('Uppsökande verksamhet') J:#pc O:#pc Personal communication**
  + **641 ('Jag tror att skickar man ut brev till alla äldre och saker per post..så kommer fler att delta') J:9.1 O:9.1**
  + 723 ('Att pensionärsorganisationer ger information om att man kan medverka aktivt') J:#pc - är egentligen svar på nästa fråga, men via medlemsorganisation vore alternativet här detta kan ju innefatta olika typer av kanaler O:    #npc (a sender that potentially can use all channels) 
  + 775 ('"webinar"') J:#pc O:9.8
  + **806 ('Inte alls') J:#nv O:#nv**
  + **825 ('Är inte särskilt intresserad vara med denna gången i och med att vi ringde') J:#nv O:#nv**
  + **853 ('via vänner och bekanta')J:#pc - är egentligen svar på nästa fråga O:#pc**

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
  + **280 ('Inte (heller) på något annat sätt') J:#nv O:#nv**
  + **60 ('...från olika myndigheter') J:10.2 + 10.3? eller #pc O:#pc: Myndigheter**
  + 113 ('Där äldre samlas på olika möten, t.ex. på vår [otolkbart] biosalongen eller samlingsal boende') J:#pc O:#nv for Q10 (the answer concerns the channel Q9 and #pc: public event) 
  + 162 ('Fackföreningar') J:#pc O:10.1
  + 181 ('Svarar i föregående fråga') (svarade "genom föreningslivet") J:#pc O:use answer from Q9 YES! 10:1 
  + **220 ('Vårdcentralen skulle kunna ha enkäter som man kan fylla i') J:10.2 O:10.2**
  + **286 ('Facebook') J:#pc eller #nv- här är det ju inte från företaget utan via kanalen Facebook, alltså är det ett svar på föregående fråga. O:#nv** 
  + **323 ('Det ska vara sjukvårdens forskare som direkt vänder sig till mig för att mina åkommor') J:10.5 (10.2?) O:10.2**
  + **356 ('Informativ sida online') - J:#pc eller #nv - liksom i fallet med facebook åsyftar svaret kanalen snarare än avsändaren. O:#nv**
  + **368 ('Genom telefonsamtal/telefonintervju') - J:#pc eller #nv - liksom i fallet med facebook åsyftar svaret kanalen snarare än avsändaren. O:#nv**
  + **459 ('Via TV-program som TV-doktorn och Fråga doktorn') J:#pc - här är det då statstelivisionen som är avsändare. O:#nv**
  + **467 ('Min läkare') J:10.2 + 10.3 O:10.2**
  + **525 ('vet ej') J:#nv O:#nv**
  + 538 ('Människor överlag som man kan lita på, som arbetar utan politisk och ekonomisk vinning') J:#pc O:10.2; 10.3; 10:5; 10:8 
  + 555 ('Beror på frågeställningen och målgrupp') J:#pc - villkorat, alltså svaret är ett ifrågasättande av frågeställningen som sådan O:#nv
  + **590 ('...av Universitetet som driver forskningsprojekt') J:10.5 O:10.5**
  + 602 ('genom kollegor') J:#pc O:10.8
  + 757 ('Ingen åsikt') J:#pc -- ska ett sådant alternativ ges? O:#nv
  + **774 ('Via brev') J:#nv - ej svar på denna fråga utan på föregående O:#nv**
  + 785 ('Vill helst av allt få information av någon personligen') J:#npv - lite för vagt för att bedöma vad som menas O:#nv
  + 825 ('vill inte bli kontaktad alls') J:10.9? alt. #pc - ny kategori 'Inte alls'? O:#nv

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
  + **6 ('Viktigt att man ser människan i forskningen och lyssnar på människan') J:#pc O:#pc: Sharing common values (Gemensam värdegrund - Personcentrering vilar på personfilosofins tankar kring vad det innebär att vara en människa)** 
  + **20 ('Att hitta lösningar på problem, som nya hjälpmedel eller ngt som är utformat fel som påverkar åldrande via dålig kvalitet på hjälpmedel som hjälper äldre som har problem med armar och ben..[...]..hemtjänsten gör ju ett jättebra fotarbete men det behövs påfyllning från forskning inte så långa glapp mellan de på golvet och forskningen läkare uppdateras men det ska även undersköterskor och de på golvet också få..är önskvärt') J:12.9 + 12.4? O:12.9**
  + **60 ('Jag är intresserad av ämnet och det motiverar mig') J:12.11 eller #pc - "viktigt" och "intressant" inte riktigt samma sak O:12.11**
  + 64 ('Att andra äldre, som kommer efter mig kan få hjälp/förbättringar genom de rön forskningen kommer fram till') J:12.4 + 12.6 + 12.9 O:12.9 eller 12.4 
  + **130 ('för att må bättre') J:#pc O:#pc: Egennytta (with subcategories see above)**
  + **136 ('att man gör något positivt för andra') J:12.4 O:12.4**
  + 155 ('Att jag själv skulle ha personlig nytta av forskningsresultatet och att andra också skulle få nytta av det') J:#pc O:12.4 AND #pc: Egennytta 
  + **161 ('Få ekonomisk ersättning') J:#pc O:#pc: att jag får ekonomisk ersättning (subkategori till egennytta)** 
  + **185 ('Ekonomisk ersättning kan motivera många') J:#pc el. #npc beroende på om man svarar för sig själv eller för andrs --- Även dig? O:#pc: att jag får ekonomisk ersättning (subkategori till egennytta)** 
  + **220 ('Att jag själv skulle få hjälp med mina problem. Att jag själv skulle få god kontakt med en forskningsexpert på min hälsa. Jag skulle tänka mig att donera min kropp så att forskarna skulle undersöka min kropp efter min död för att kunna bidra till ett svar på vad det är jag lider av') J:12.3 + 12.4 O:12.3 AND 12:4** 
  + 321 ('Om jag blev kontaktad så skulle jag vara motiverad') J:#nv O:#pc: Att någon frågade OR 12.2 
  + **323 ('Att få veta vad forskningen kommer att leda till i framtiden för mina barn och barnbarn. Att jag känner att jag litar på forskarna skulle motivera mig att delta') - J:här är det två svar 12.10 + tilltro till forskare #pc O:12.10 AND #pc: Sharing common values (Gemensam värdegrund - känsla av tillit)**
  + **327 ('Brist på tid') J:#nv O:#nv (svar på annan Q om hinder)** 
  + **339 ('Att få känna mig trygg') J:#pc O:#pc Sharing common values (Gemensam värdegrund - känsla av trygghet)** 
  + **367 ('ersättning') J:#pc O:#pc: att jag får ekonomisk ersättning (subkategori till egennytta)** 
  + **375 ('Att jag får förtroende för forskare') J:#pc O:#pc Sharing common values (Gemensam värdegrund - känsla av förtroende)** 
  + **448 ('Ekonomisk ersättning vore bra') J:#pc O:#pc: att jag får ekonomisk ersättning (subkategori till egennytta)**
  + **452 ('...om det handlar om sjukvård och mediciner som blir bättre') J:12.9 O:12.9**
  + 459 ('Intresse för ämnet. Jag vill få mer kunskap i ämnet') J:#pc - de nuvarande kategorierna täcker inte riktigt in vad detta svar omfattar O:12.11
  + **520 ('Samhällsnyttan och för den enskilda individen är viktig') J:12.4 + lite vagt vad 'den enskilda individen åsyftar #npc O:12:4 AND #pc: Egennytta**
  + **538 ('Om jag blev kontaktad av rätt personer som jag känner förtroende för') J:#pc - återigen förtroende O:#pc: Sharing common values (Gemensam värdegrund - känsla av förtroende)** 
  + **590 ('Om jag själv skulle kunna få en bättre hälsa av att delta') J:#pc O:12.1 OR #pc: Egennytta** 
  + **634 ('Politiker tar del av forskningen och använder sig av den i praktiken') J:#pc O:12.4 OR #pc: Att det verkligen leder till förändring!** 
  + 733 ('För att jag själv är i den målgruppen') J:#npc - lite för vagt för att kunna kategorisera O:#pc: Att jag har erfarenheter som jag kan bidra med OR (tolkningsfråga) #pc: Egennytta. 
  + **775 ('viktigt område och behöver belysas') J:12.11 O:12.11**
  + **779 ('Om jag fick en seriös förfrågan, beroende på vem som ställer frågan. Om det är en seriös aktör så är jag intresserad') J:#pc - återigen förtroende O:#pc: Sharing common values (Gemensam värdegrund - känsla av tillit) AND #pc: Att någon frågade** 
  + 781 ('Att det sker i --- kommun') J:#pc - återigen villkorat denna gång beroende på var O:#nv (Svar på annan fråga om hinder – att det kan vara för långt bort?) 
  + **810 ('Professionell nivå på forskningen med lämplig ersättning') J:#pc - återigen kopplat till forskningens seriositet + ersättning O:#pc: Sharing common values (Gemensam värdegrund - känsla av tillit) AND #pc: att jag får ekonomisk ersättning (subkategori till egennytta)** 
  + **818 ('Forskning som verkligen kan göra skillnad. Bli mer involverad, inte bara informerad') J:#pc - återigen villkorat avhängit forskningens kvalitet O:12.4 OR #pc: Att det verkligen leder till förändring!**
  

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
  + **20 ('Det skulle vara att ämnet ligger oerhört långt från mig, men det är bara ett antagande') J:#pc - om den omfattar ämne jag inte kan knyta an till O:#pc: Att jag inte tror att jag har de erfarenheter som efterfrågas** 
  + **35 ('Fysiskt avstånd') J:#pc - vi har bara angett tid, skulle behöva addera distans O:#pc: Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)**
  + **49 ('Ämne som inte intresserar mig') J:#pc - ämne som intresserar mig O:#pc: Brist på intresse för ämnet** 
  + **53 ('Dofter. Min fru har SHR och dofter fastnar i hår och kläder, vilket jag då tar med hem och kan orsaka symptom för henne. KOL har jag själv och därför är dofter inte heller bra för mig.') J:13.8 (#pc egen eller anhörigs sjukdom kanske skulle förtydligas) O:13.8**
  + 58 ('Jag upplever att jag är för gammal') - J:13.8 el #pc - frågan hur "privat" ett försämrat hälsotillstånd pga ålder är. O:13.7
  + **60 ('Eventuell brist på intresse för det aktuella ämnet') J:#pc O:#pc: Brist på intresse för ämnet** 
  + 64 ('Att, såsom varande icke-akademiker, har svårt att förstå vad som förväntas av mig och hur jag kan bidra konstruktivt.') J:13.1 O:13.3 + 13.3
  + 82 ('Om jag känner att jag nödvändigt måste delta är det ngt annat, men jag är gammal...') J:#pc O:13.7
  + **96 ('anhörigvårdare') J:13.8? O:13.8**
  + **99 ('Smärtsamma prover/tester') J:13.7 O:13.7**
  + **117 ('Eventuellt brist på intresse') J:#pc O:#pc:Brist på intresse för ämnet**
  + 124 ('Är idag frisk och vital men om detta förändras negativt är det naturligtvis ett hinder') J:13.8? O:13.7
  + 129 ('Att man saknar de rätta grundkunskaperna om t.ex. tillvägagångssätt') J:13.1? el. 13.7? O:13.1 + 13.2
  + **137 ('Förbättringar för andra') J:#nv O:#nv(jag tolkar som svar på Q12)**
  + **175 ('Är ofta utomlands') J:#pc O:#pc: Physical distance to research site (Svårigheter att infinna mig om forskningen genomförs på en viss plats)**
  + 210 ('Ett hinder kan vara att personer i fyrtioårsåldern dominerar i samhället') J:#npc - lite oklart argument O:13.4
  + **225 ('Ovilja att vara med helt enkelt') J:#pc ointresse för ämnet O:#pc: Brist på intresse för ämnet** 
  + **234 ('Vill inte hålla på med stillasittande administration') J:#pc O:#pc: Brist på intresse för ämnet** 
  + 252 ('finns inga hinder förutsatt att jag förstår det jag ska göra') J:13.1 O:13.2 + 13.3
  + **266 ('om jag måste åka till annan ort som jag inte känner mig bekväm med') J:#pc O:#pc: (Physical) distance to research site (Svårigheter att infinna mig om forskningen genomförs på en viss plats)**
  + **267 ('Jag tycker jag kanske inte kan se relevansen i vissa saker, att jag inte förstår riktigt varför man ska forska om just det') J:#pc O:#pc: Brist på relevans – det kommer verkligen inte att göra någon skillnad** 
  + **292 ('Om det skulle kosta mig rent ekonomiskt') J:#pc - ekonomi O:#pc: Ingen ekonomisk ersättning.** 
  + **297 ('jag är inte motiverad') J:#pc O:#pc: Brist på intresse/motivation för ämnet** 
  + **314 ('Att forskningsområdet inte känns viktigt') J:#pc O:#pc: Brist på relevans – det kommer verkligen kan göra någon skillnad** 
  + **315 ('Tycker både ja och nej delvis på alla frågor. För många och för lika alternativ.') J:#nv -- kritik mot sättet frågan är formulerad O:#nv ELLER #pc: I don’t know** 
  + **316 ('Dålig inriktning, onödigt forskningsmål') J:#pc O:#pc: Brist på relevans – det kommer verkligen inte att göra någon skillnad** 
  + **317 ('om de inte skulle intressera mig, ett smalt ämne där jag ej har intresse exempelvis') J:#pc O:#pc: Brist på intresse för ämnet** 
  + **323 ('Att jag inte skulle käna tillit till forskarna skulle vara ett hinder att delta') J:#pc tillit O:#pc: Not shared common value. (Brist på gemensam värdegrund - avsaknad av tillit) ELLER 13.3** 
  + **331 ('Gammal, borde vara pigare för att orka med') J:13.7 O:13.7**
  + **336 ('Ointresse') J:#pc O:#pc: Brist på intresse för ämnet**
  + **341 ('jag är inte intresserad') J:#pc O:#pc: Brist på intresse för ämnet** 
  + **367 ('Upplägg och omfattning. Vet inget om ämnet') J:#pc O:#pc: Att jag inte tror att jag har de erfarenheter som efterfrågas** 
  + **375 ('Att jag får förtroende för forskarna och att dom lyssnar på oss som deltar och medborgarna gör dom ej det vill jag inte vara med') J:#pc tillit och förtroende O:#pc: Not shared common value. (Brist på gemensam värdegrund - avsaknad av tillit) ELLER 13.3** 
  + 378 ('min ålder - 97 år') J:#pc el. 13.8 O:13.7
  + **379 ('Projekt som jag inte anser meningsfulla') J:#pc O:#pc: Brist på relevans – det kommer verkligen inte att göra någon skillnad** 
  + 387 ('Min ålder=85 år') J:#pc O:13.7
  + **392 ('Svårt att välja svar') J:#nv -- kritik mot frågan O:#nv ELLER #pc: I don’t know**
  + **402 ('Integritetsskyddet') J:#pc - tillit förtroende O:#pc: Issues of the protection of privacy** 
  + **408 ('Hörselnedsättning') J:13.7? + 13.8? O:13.7**
  + **409 ('Om man uppfattar det som otydlig och dålig kvalitet på forskningen kan det vara ett hinder för mig att delta aktivt i den') J:#pc O:#pc: Brist på relevans – det kommer verkligen inte att göra någon skillnad ELLER 13.3**
  + **411 ('Kostnader för att delta') J:#pc O:#pc: Ingen ekonomisk ersättning**
  + **423 ('Ej intresserad') J:#pc O:#pc: Brist på intresse för ämnet**
  + **430 ('inget') J:#pc -- inget-kategori saknas O:#nv ELLER #pc: Inget hindrar mig idag!**
  + **445 ('Kan inte svara på denna fråga') J:#nv O:#nv ELLER #pc: I don’t know**
  + 448 ('Känner sig inte som äldre') J:13.2? -- lite oklart vad detta kan kategoriseras som O:#pc: Att jag inte tror att jag har de erfarenheter som efterfrågas 
  + 452 ('Jag hittar inget hinder, kan delta, men isf skulle det vara sjukdom om jag ej kan') J:13.8 O:#nv ELLER #pc: inget hindrar mig idag!
  + **462 ('Jag är inte intresserad') J:#pc O:#pc: Brist på intresse för ämnet**
  + 471 ('Min höga ålder (92 år)') J:#13.8 O:13.7
  + **482 ('Vill ej vara med') J:#pc O:#pc: Brist på intresse för ämnet**
  + **508 ('Forskningens fokus, vilka frågor som utforskas') J:#pc O:#pc: Brist på intresse för ämnet** 
  + **519 ('Avstånd') J:#pc O:#pc: Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)** 
  + 521 ('Jag är gammal och har gjort mitt för samhället') J:#pc O:13.7
  + **522 ('ser inget hinder att deltaga') J:#pc O:#nv ELLER #pc: Inget hindrar mig idag!**
  + 538 ('min ålder i sådana fall, är en gammal gubbe') J:#pc O:13.7
  + **546 ('Inte motiverad') J:#pc O:#pc: Brist på intresse/motivation för ämnet**
  + 564 ('Hög åldern är en svårighet') J:#pc O:13.7
  + **576 ('Vet ej') J:#nv O:#nv ELLER #pc: I don’t know**
  + **577 ('Vill inte') J:#pc O:#pc: Brist på intresse för ämnet** 
  + **581 ('Inget egentligt intresse') J:#pc O:#pc: Brist på intresse för ämnet** 
  + 590 ('Jag arbetar fortfarande') J:13.6? (här anges att man är upptagen med annat, implicit att man inte har tid) O:13.8
  + **605 ('Kommunikationen att ta sig till möten') J:#pc O:#pc: Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)**
  + 606 ('Beroende på omfattning') J:#pc -- återigen det beror på O:13.7
  + **669 ('Bra att många ställer upp') J:#nv O:#nv (svar på annan fråga)**
  + 674 ('fysisk handikapp, åldern') J:#pc O:13.7
  + **696 ('vet ej') J:#nv O:#nv ELLER #pc: I don’t know**
  + **698 ('Brist på intresse') J:#pc O:#pc: Brist på intresse för ämnet**
  + **725 ('Måttligt intresserad') J:#pc O:#pc: Brist på intresse för ämnet** 
  + 738 ('åldersrelaterat och har svårt att medverka på grund av att jag bor långt borta') J:#pc O:13.7 AND #pc: Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs) 
  + 764 ('I min ålder blir jag lat och bekväm') J:13.8? O:13.7
  + **765 ('Ingenting specifikt skulle hindra mig från att deltaga') J:#pc - 'inget' saknar kategori O:#nv ELLER #pc: Inget hindrar mig idag!** 
  + **775 ('Ser inget hinder egentligen, gäller ju plats och tidpunkt') J:#pc O:#nv ELLER #pc: Inget hindrar mig idag! OCH/ELLER #pc: Physical distance to research site (Svårigheter att infinna mig på den plats där forskningen genomförs)** 
  + **779 ('Om det inte är tillräckligt intressant då ä det ett hinder för mig') J:#pc O:#pc: Brist på intresse för ämnet** 
  + **781 ('Ingen bil. Får inte kosta pengar, typ tågbiljett') J:#pc O:#pc: Ingen ekonomisk ersättning.**
  + 783 ('Jag vill ha en bred information innan vad forskningen handlar om i detalj och vad den leder till..') J:#pc -- återigen villkorat O:13.3
  + **785 ('Forskarna som ofta är för unga för att förstå hur en gammal människa känner') J:13.3 (13.4?) O:13.3 ELLER 13.4**
  + 791 ('Jag har det bra som det är och har inte tid, då skulle min vardag ändras och det vill jag ej') J:13.6 + 13.8 O:#pc: Brist på intresse för ämnet AND 13.6 
  + **810 ('Beredd att medverka som testperson av utveckling med datastyrda hjälpmedel') J:#pc -- villkorat, beror på område O:#nv ELLER #pc: Inget hindrar mig idag!**
  + **861 ('Är det inte intressant vill jag ej vara med') J:#pc O:#pc: Brist på intresse för ämnet** 
  + **864 ('Min uppfattning att forskningens integritet kan rubbas') J:#pc O:#pc: Forskningens oberoende kan hotas**
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

