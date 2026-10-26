# Genomsnittsmetoden

Omkostnadsbeloppet för bitcoin och liknande kryptotillgångar beräknas med genomsnittsmetoden (52 kap. 3 § inkomstskattelagen). Högsta förvaltningsdomstolen har sagt att det är genomsnittsmetoden i 48 kap. 7 § som ska användas (mål 2674-18).

Schablonmetoden får inte användas. Se `belopp-och-skattesatser.md`.

## Ett genomsnitt per kryptovaluta

Alla köp, försäljningar och växlingar av samma kryptovaluta ingår, oavsett plånbok och oavsett om växlaren är centraliserad eller decentraliserad. Bitcoin, ether och ripple räknas var för sig. En stablecoin som speglar en fiatvaluta är en egen tillgång, skild från fiatvalutan.

Köp gjorda före inkomståret ingår. Försäljningar före inkomståret minskar poolen. Saknas ingående antal och ingående omkostnadsbelopp, med underlag: räkna inte.

## Så räknar du

Gör ett arbetsblad per kryptovaluta. Sortera alla händelser i tidsordning. Börja med ingående antal och ingående omkostnadsbelopp, eller med noll om den första händelsen är det första köpet.

Vid varje anskaffning: öka antalet och öka det totala omkostnadsbeloppet med anskaffningsutgiften i svenska kronor. Köpsavgift i fiat läggs till anskaffningsutgiften.

Vid varje avyttring:

1. Genomsnitt = totalt omkostnadsbelopp / totalt antal.
2. Omkostnadsbelopp för det sålda = genomsnitt × antal sålda.
3. Vinst eller förlust = försäljningspris − omkostnadsbelopp.
4. Minska poolens antal med det sålda antalet.
5. Minska poolens omkostnadsbelopp med omkostnadsbeloppet för det sålda.

Nästa köp läggs på det som är kvar. Genomsnittet räknas om.

Skatteverkets exempel (Dogecoin, sidan Kryptovalutor):

| Händelse | Antal i poolen | Omkostnadsbelopp i poolen | Genomsnitt | Resultat |
|---|---|---|---|---|
| Köp 10 för 10 000 kr, sedan 10 för 50 000 kr | 20 | 60 000 kr | 3 000 kr | |
| Sälj 15 för 60 000 kr | 5 | 15 000 kr | 3 000 kr | vinst 15 000 kr |
| Köp 5 för 25 000 kr | 10 | 40 000 kr | 4 000 kr | |
| Betala varor med 0,345, försäljningspris 2 000 kr | 9,655 | 38 620 kr | 4 000 kr | vinst 620 kr (omkostnadsbelopp 1 380 kr) |
| Sälj 5 för 15 000 kr | 4,655 | 18 620 kr | 4 000 kr | förlust 5 000 kr |

Förlusten på 5 000 kronor redovisas i sin helhet. Avdraget blir 3 500 kronor när Skatteverket kvoterar (5 000 × 70 procent). Vinsterna 15 000 och 620 redovisas som vinst, tillsammans 15 620 kronor. Ingen kvittning på blanketten.

Anelas exempel, när bara en del säljs: 0,5 bitcoin för 20 000 kronor och 0,2 bitcoin för 10 000 kronor, sedan 0,4 bitcoin för 40 000 kronor. Omkostnadsbelopp 17 143 kronor, vinst 22 857 kronor. Se avrundningen i `belopp-och-skattesatser.md`.

Har hela innehavet av samma slag sålts vid ett enda tillfälle, och det inte har funnits någon delförsäljning tidigare: dra av det som betalats från försäljningspriset. En genomsnittsberäkning behövs inte, eftersom allt säljs på en gång.

## Anskaffningsutgift

| Hur kryptovalutan fick | Anskaffningsutgift | Källa |
|---|---|---|
| Köp mot svenska kronor | Det som betalades, plus köpavgift | Rättslig vägledning, exemplet Francis |
| Köp mot fiatvaluta | Fiatvalutans värde i svenska kronor | Rättslig vägledning |
| Byte mot annan kryptovaluta | Marknadsvärdet av det som togs emot, i svenska kronor | Sidan Kryptovalutor |
| Lön eller annan tjänsteinkomst | Marknadsvärdet som tas upp i tjänst | Sidan Kryptovalutor |
| Mining | Marknadsvärdet vid tilldelningen, samma belopp som tas upp som hobby eller näring | Sidan Kryptovalutor |
| Stakingbelöning i ether | Marknadsvärdet när belöningen kan disponeras, samma belopp som tas upp vid punkt 7.2 | Ställningstagande om staking av ether |
| Ränta i kryptovaluta | Marknadsvärdet vid tilldelningen, samma belopp som tas upp vid punkt 7.2 | Sidan Kryptovalutor, exemplen Sören och Rosa |
| Arv, gåva eller annat benefikt fång | Den tidigare ägarens anskaffningsutgift | 44 kap. 21 § inkomstskattelagen |
| Airdrop eller hard fork | Inget generellt svar på de sidor som kontrollerades 26 oktober 2026. Sätt inte omkostnadsbeloppet till noll | Se `handelser.md` |

## Transaktionsavgifter

Källa: rättslig vägledning, avsnittet Transaktionsavgifter. Lagrummen som nämns där är 44 kap. 13 § (försäljningsutgifter får dras av) och 42 kap. 6 § inkomstskattelagen (förvaltningsutgifter får inte dras av).

- En avgift som tas ut för att en avyttring ska ske minskar försäljningspriset.
- En avgift vid köp ökar anskaffningsutgiften.
- En flyttavgift mellan två plånboksadresser, utan direkt samband med en avyttring, påverkar inte kapitalvinsten. Den dras inte av.

Skatteverkets exempel, köp och försäljning: Francis köper 0,1 för 30 000 kronor och betalar 100 kronor i avgift. Anskaffningsutgiften är 30 100 kronor. Han säljer för 32 000 kronor och betalar 100 kronor. Försäljningspriset är 31 900 kronor. Vinst 1 800 kronor.

Betalas avgiften med kryptovaluta anses den kryptovalutan också avyttrad.

Skatteverkets exempel, byte: Indira har 100 X-coin, omkostnadsbelopp 20 000 kronor, genomsnitt 200 kronor. Hon byter 10 X-coin mot 100 Y-coin. Marknadsvärdet är 3 000 kronor. Avgiften är 0,2 X-coin, värda 60 kronor.

- 10 X-coin: försäljningspris 3 000 − 60 = 2 940 kronor. Omkostnadsbelopp 2 000 kronor. Vinst 940 kronor.
- 0,2 X-coin: försäljningspris 60 kronor. Omkostnadsbelopp 40 kronor. Vinst 20 kronor.
- Tillsammans 960 kronor. Samma resultat om 10,2 X-coin räknas som sålda för 3 000 kronor mot omkostnadsbelopp 2 040 kronor.
- Anskaffningsutgiften för 100 Y-coin är 3 000 kronor, alltså marknadsvärdet av det som togs emot, inte 2 940.

Använd det ena sättet. Inte båda. Kontrollera att summan blir densamma.

## Förenklad redovisning ändrar inte beräkningen

Varje affär måste räknas var för sig så att det syns vilka som är vinster och vilka som är förluster. På blanketten får vinstaffärerna sedan summeras för sig och förlustaffärerna för sig, per kryptovaluta. Se `k4-avsnitt-d.md`.

## Källor

- Skatteverket: [Kryptovalutor](https://www.skatteverket.se/privat/skatter/vardepapper/andratillgangar/kryptovalutor.4.15532c7b1442f256bae11b60.html)
- Skatteverket: [Särskilt om kryptotillgångar i inkomstslaget kapital](https://www4.skatteverket.se/rattsligvagledning/edition/2025.1/409288.html)
- Skatteverket: [HFD 2674-18](https://www4.skatteverket.se/rattsligvagledning/373946.html?date=2018-12-17)
- Skatteverket: hjälpblankett SKV 2198, Genomsnittligt omkostnadsbelopp, länkad från sidan Kryptovalutor. Lämnas inte in.
- Skatteverket: Beräkningshjälp för omkostnadsbelopp, länkad från sidan Kryptovalutor. I första hand gjord för aktier. Samma genomsnittsmetod gäller för ett mindre antal kryptoaffärer.
