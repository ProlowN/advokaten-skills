# Vilka händelser som ska med

Med avyttring avses försäljning, byte och därmed jämförlig överlåtelse (44 kap. 3 § inkomstskattelagen). Det finns ingen särskild definition av kryptotillgång i inkomstskattelagen. Bitcoin beskattas som andra tillgångar och som kapitalplaceringstillgång, inte som delägarrätt och inte som fiatvaluta (HFD 2674-18 och Skatteverkets ställningstagande från 2014-04-23).

Allt nedan redovisas i svenska kronor. Omkostnadsbeloppet räknas enligt `genomsnittsmetoden.md`.

## Det här ska en privatperson deklarera

Skatteverket räknar upp följande exempel. Redovisningen sker på bilaga K4 avsnitt D, tillsammans med inkomstdeklarationen.

| Händelse | Försäljningspris | Vad som händer med det som tas emot |
|---|---|---|
| Försäljning mot fiatvaluta | Fiatvalutans värde i svenska kronor | Fiatvalutan kan själv behöva redovisas på K4 avsnitt C |
| Byte mot en eller flera andra kryptovalutor | Marknadsvärdet av det som tas emot | Samma belopp blir anskaffningsutgift för den nya kryptovalutan |
| Betalning för en vara eller en tjänst | Marknadsvärdet av varan eller tjänsten | |
| Utlåning, när mottagaren får förfoga fritt över kryptovalutan | Marknadsvärdet vid utlåningen | En fordran uppstår, med samma belopp som anskaffningsutgift. Återbetalningen är en avyttring av fordran |
| Kryptovaluta som spelinsats | Sidan säger att insatsen ska deklareras, men visar inte hur försäljningspriset sätts | Räkna inte ett belopp utan underlag. Se avsnittet Spel |

Källa: Skatteverket, sidan Kryptovalutor, och rättslig vägledning, avsnitten Byte och Utlåning.

## Det här ska inte deklareras som avyttring

- Värdeuppgång eller värdenedgång på sådant som inte har avyttrats.
- Flytt mellan egna plånböcker, när äganderätten inte går över. Flyttavgiften är inte en försäljningsutgift och dras inte av (rättslig vägledning, Transaktionsavgifter).
- Förvaring hos någon annan, eller pantsättning, om mottagaren inte får sälja, byta eller låna ut tillgången. Äganderätten har inte gått över.
- Förlorad kontroll. En borttappad nyckel, eller en hackerattack mot en handelsplats, ger inte i sig rätt till förlustavdrag. Det är inte en avyttring.
- Staking av ether genom att 32 ether registreras som insats i nätverket. Skatteverket jämställer det med en deponering. Själva insatsen är ingen avyttring. Belöningen är däremot skattepliktig, se nedan.
- Wrapping från ether till WETH, när den sker automatiskt som ett led i en längre transaktionskedja. Det är Skatteverkets uppfattning i exemplet om decentraliserat lån. En fristående wrapping har inget eget svar på sidan. Fråga Skatteverket innan den behandlas som en växling eller som en icke-händelse.

## Utlåning, pant och likviditetspool

Avgör med användarvillkoren, inte med vad tjänsten kallas.

- Mottagaren får sälja eller annars förfoga fritt: utlåningen är en avyttring. Det gäller även mellan privatpersoner. Vid återbetalningen avyttras fordran. Marknadsvärdet av det som kommer tillbaka är försäljningspris för fordran och anskaffningsutgift för den återfådda kryptovalutan. Fordran som inte är i svenska kronor eller fiatvaluta redovisas också på K4 avsnitt D (52 kap.).
- Bara pant eller förvaring, utan rätt för mottagaren att omsätta tillgången: ingen avyttring, varken vid insättningen eller när tillgången kommer tillbaka. Säljs panten för att lånet inte betalas är det en avyttring för den som ägde kryptovalutan.
- Likviditetspool mot en token som representerar andelen: byte, alltså avyttring. Inlösen av token är en ny avyttring. Försäljningspriset är marknadsvärdet av det som tas emot.
- Ökar poolens förmögenhet utan att innehavaren får nya token: ingen löpande inkomst. Värdeökningen kommer med när token löses in.
- Delas nya token ut som ett direkt resultat av poolens verksamhet: löpande inkomst av kapital vid tilldelningen, punkt 7.2. Marknadsvärdet blir anskaffningsutgift för de nya token.
- Ränta i fler kryptovalutor, till exempel hos en centraliserad låneplattform eller som nya token i en decentraliserad låneplattform: punkt 7.2. Samma belopp blir anskaffningsutgift.

Källor: sidan Kryptovalutor (frågan om överföring till plattform, och exemplen Sören, Nico, Claudia, Rosa och Malin) och rättslig vägledning (utlåning, likviditetspool, rebase).

En rebase som bara ändrar antalet och lämnar det samlade värdet oförändrat, hos alla innehavare och utan resultatfördelning, är inte en löpande inkomst. Antalet i genomsnittsberäkningen behöver då justeras utan att en inkomst tas upp. Skatteverket beskriver det i exemplet om rebase. Använd det bara när händelsen har de kännetecknen.

## Staking, mining, lön och ränta

**Staking av ether i en egen nod (32 ether, proof of stake).** Insatsen är ingen avyttring. Belöningen är avkastning på det egna innehavet och tas upp i kapital vid punkt 7.2 med marknadsvärdet när den kan disponeras. Samma belopp är anskaffningsutgift. Från april 2023 kan belöningen tas ut, och den tas upp det år den tilldelas. Ställningstagandet gäller ether. Källa: sidan Kryptovalutor och ställningstagandet Staking av ether i Ethereum 2.0, 2021-12-14, dnr 8-1369233.

**Annan staking.** Ordet används för olika saker: proof of stake, inlåsning, utlåning och pant. Skatteverket har inget ställningstagande som täcker alla. Låsning via en pool där deltagaren får en token för de insatta tillgångarna plus avkastningen är ett byte och alltså en avyttring. Inlösen av den token är en ny avyttring. Annan staking: klassa inte själv. Hänvisa till rättslig vägledning, avsnittet Staking, och till Skatteverket.

**Mining.** Inkomsten tas normalt upp som tjänst (hobby). Den kan undantagsvis vara näringsverksamhet. Näringsverksamhet ligger utanför den här skillen. Omkostnadsbeloppet i kapital är marknadsvärdet i svenska kronor vid tilldelningen, samma belopp som tas upp i hobby eller näring. Själva tilldelningen redovisas inte på K4. En senare försäljning gör det. Hobbyinkomsten hör hemma i inkomstdeklaration, bilaga T2. Källa: sidan Kryptovalutor och rättslig vägledning, Mining av bitcoin.

**Lön i kryptovaluta.** Tas upp i tjänst. Omkostnadsbeloppet vid en senare avyttring är marknadsvärdet när ersättningen togs emot, alltså det belopp som redovisats i tjänst. Källa: sidan Kryptovalutor.

**Betalning i en näringsverksamhet.** Utanför skillen, utom detta: den senare värdeförändringen tas normalt upp i kapital, om kryptovalutan inte är lagertillgång. Omkostnadsbeloppet är det bokförda värdet inklusive moms. Källa: exemplet Olof på sidan Kryptovalutor.

## Spel

Att använda kryptovaluta som spelinsats står på listan över sådant som ska deklareras, på K4 avsnitt D. Sidan visar inte vilket försäljningspris insatsen ska ha. Sätt inget belopp utan ett underlag som användaren kan visa, och säg att beräkningen behöver stämmas av med Skatteverket om underlaget inte räcker.

Vinst i lotteri och vid vadhållning tas, enligt samma sidas svar om onecoin, upp som kapitalinkomst om vinsten överstiger 100 kronor och inte är skattefri. Skattefrihet kräver i regel att den som tillhandahåller spelet i Sverige har licens. Vinst i pyramidspel är alltid skattepliktig, och förlust får inte dras av. Onecoin är enligt Skatteverket ett pyramidspel, inte en kryptovaluta.

Skilj på insatsen (avyttring av kryptovalutan) och själva spelvinsten. Är det oklart om arrangören har svensk licens: räkna inte vinsten som skattefri. Hänvisa till Skatteverket.

## Airdrop och hard fork

De sidor som kontrollerades 26 oktober 2026 ger inget generellt svar om airdrop, och inget generellt svar om hard fork.

Det enda som sägs om hard fork är att bitcoin cash, skapad genom en hard fork efter att Mt. Gox stängde, inte påverkar omkostnadsbeloppet för fordran på Mt. Gox.

Gör därför inte något av detta:

- ta upp airdropen vid punkt 7.2 med ett uppskattat värde
- sätta omkostnadsbeloppet till noll
- behandla forken som en avyttring av den ursprungliga kryptovalutan

Lägg händelsen åt sidan. Säg att användaren behöver ett svar från Skatteverket innan den kryptovalutan kan räknas. Har användaren ett skriftligt svar: följ det och spara det med underlagen.

## Gåva och arv

En ren gåva är inte en avyttring. Mottagaren tar över givarens anskaffningsutgift (44 kap. 21 § inkomstskattelagen). Detsamma gäller arv. Be om underlag som visar givarens omkostnadsbelopp och antal. Saknas det: räkna inte.

Säljs kryptovalutan under marknadsvärdet till någon närstående kan det vara delvis gåva. Det ligger utanför skillen. Hänvisa till Skatteverket.

## Fiatvaluta

Köp med euro eller dollar är en avyttring av fiatvalutan. Försäljning mot euro eller dollar är ett förvärv av fiatvalutan. Redovisa fiatvalutan på K4 avsnitt C. Trettiodagarsregeln och kursen står i `belopp-och-skattesatser.md`.

## FTX, Celsius och Mt. Gox

Årets belopp för FTX står i årsfilen. Celsius och Mt. Gox har långa svar på sidan Kryptovalutor. Läs det svar som gäller användaren innan du räknar. I korthet, enligt sidan:

- Utlåning till Celsius var en avyttring redan när tillgångarna fördes över, eftersom Celsius fick förfoga över dem. Förlust på fordran kräver att fordran har avyttrats. Chapter 11 är inte konkurs. Återbetalning från den 1 februari 2024 är en avyttring av fordran. Skatteverket ber den som yrkar förlust att göra ett öppet yrkande under Övriga upplysningar, på grund av oklarheter kring hur återbetalningen gått till.
- Mt. Gox: fordran är i yen. Försäljning eller återbetalning redovisas på K4 avsnitt D. Den del av en förlust som beror på valutakursen redovisas på K4 avsnitt C. Omkostnadsbeloppet för fordran kan beräknas till det omkostnadsbelopp kryptovalutan och fiatvalutan hade när verksamheten stängde 2014.

## Certifikat och CFD

Ett certifikat med bitcoin som underliggande tillgång redovisas på K4 avsnitt D. Det är inte samma sak som att äga bitcoin, och det ingår inte i genomsnittet för bitcoin. Skatteverkets exempel för inkomstår 2025: certifikatet BTCX2, köpt för 177 000 kronor (175 000 plus courtage 2 000), sålt för 175 400 kronor, förlust 1 600 kronor till punkt 8.4.

CFD med valuta som underliggande egendom redovisas på K4 avsnitt C. Hela förlusten får dras av. CFD med råvara som underliggande egendom redovisas på K4 avsnitt D, och förlusten kvoteras till 70 procent. En CFD eller perpetual med kryptovaluta som underliggande har ingen egen rad i Skatteverkets tabell. Rättslig vägledning säger att ett derivat med kryptotillgång som underliggande beskattas enligt 52 kap., eftersom den underliggande egendomen styr. Gissa inte avsnitt. Läs prospektet och tabellen Så redovisar du olika värdepapper, eller hänvisa till Skatteverket.

Har användaren handlat CFD under 2025 hos CMC Markets, IG Markets, Skilling eller RoboMarkets kan resultatet redan stå i specifikationen och vara förifyllt. Redovisa det då inte en gång till på K4. Källa: Skatteverket, Exempel för dig som ska deklarera aktier och övriga värdepapper.

## Källor

- Skatteverket: [Kryptovalutor](https://www.skatteverket.se/privat/skatter/vardepapper/andratillgangar/kryptovalutor.4.15532c7b1442f256bae11b60.html)
- Skatteverket: [Särskilt om kryptotillgångar i inkomstslaget kapital](https://www4.skatteverket.se/rattsligvagledning/edition/2025.1/409288.html), utgåva 2025.1
- Skatteverket: [Staking av ether i Ethereum 2.0](https://www4.skatteverket.se/rattsligvagledning/edition/2025.1/401273.html)
- Skatteverket: [HFD 2674-18](https://www4.skatteverket.se/rattsligvagledning/373946.html?date=2018-12-17)
- Skatteverket: [Deklarera aktier och övriga värdepapper](https://www.skatteverket.se/privat/skatter/vardepapper/deklareraaktierochovrigavardepapper.4.5c281c7015abecc2e201bbd1.html)
- Skatteverket: [Exempel för dig som ska deklarera aktier och övriga värdepapper](https://www.skatteverket.se/privat/skatter/vardepapper/deklareraaktierochovrigavardepapper/deklareravardepapperexempel.4.7afdf8a313d3421e9a9519.html)
- [Inkomstskattelag (1999:1229)](https://www.riksdagen.se/sv/dokument-och-lagar/dokument/svensk-forfattningssamling/inkomstskattelag-19991229_sfs-1999-1229/) 44 kap. 3 och 21 §§, 52 kap.
