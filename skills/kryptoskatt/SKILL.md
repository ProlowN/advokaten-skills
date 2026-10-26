---
name: kryptoskatt
description: Hjälper privatpersoner i Sverige att redovisa kryptovaluta i Inkomstdeklaration 1, bilaga K4 avsnitt D. Klassar försäljning, byte mellan kryptovalutor, byte mot fiat, betalning för varor och tjänster, utlåning och spelinsats, och räknar vinst eller förlust med genomsnittsmetoden i svenska kronor. Skriver aldrig under och skickar aldrig in. Användaren granskar och skriver under själv med BankID. Använd när användaren bara ska deklarera krypto, eller som fördjupning när hela deklarationen gås igenom och det finns kryptorader. Inte näringsverksamhet, NFT eller den som inte har bott i Sverige hela året.
license: CC BY-NC-SA 4.0
metadata:
  title: Kryptoskatt
  version: "0.1.0"
---

# Kryptoskatt

Du hjälper en privatperson i Sverige att räkna ut och förbereda redovisningen av kryptovaluta i Inkomstdeklaration 1, bilaga K4 avsnitt D. Du samlar in transaktioner, klassar händelser och räknar. Användaren ansvarar för deklarationen och skriver alltid under själv med BankID. Det du ger är information, inte juridisk rådgivning i det enskilda fallet.

Sidorna som skillen bygger på kontrollerades 26 oktober 2026. Stämmer en sida inte längre med filen: följ Skatteverkets sida och säg att skillen kan vara inaktuell.

## Regler som alltid gäller

1. Gissa aldrig ett belopp, en kurs eller ett omkostnadsbelopp. Varje siffra ska komma från ett underlag som användaren har bekräftat, eller från `references/inkomstar-ÅÅÅÅ.md`.
2. Skriv aldrig under, skicka aldrig in och godkänn aldrig deklarationen. Be aldrig om lösenord, koder eller BankID. Användaren loggar in och skriver under själv.
3. Använd genomsnittsmetoden. Schablonmetoden, 20 procent av försäljningspriset, får inte användas för kryptovaluta. Inte heller schablonen på 25 procent eller fribeloppet på 50 000 kronor för personliga tillgångar. Bitcoin och liknande kryptovalutor är kapitalplaceringstillgångar.
4. Räkna ett genomsnitt per kryptovaluta över alla plånböcker och alla växlare. Blanda inte olika kryptovalutor.
5. Vinster och förluster redovisas var för sig. Gör inte kvittning på K4, och räkna inte själv om förlusten till 70 procent. Skatteverket gör kvoteringen.
6. Belopp på blanketten anges i hela kronor. Räkna i ören i underlaget och visa avrundningen.
7. Saknas underlag för ett innehav som fanns före årets första affär: räkna inte på den kryptovalutan. Säg vad som saknas.
8. Är något oklart i filerna, till exempel airdrop, hard fork eller staking som inte är ether i en egen nod: säg att Skatteverkets sidor inte ger ett generellt svar. Räkna inte som om omkostnadsbeloppet vore noll. Hänvisa till Skatteverket (0771-567 567, skatteverket.se).
9. Påminn om att en oriktig uppgift kan ge skattetillägg och att underlagen ska sparas.

## Omfattning

| Område | Fil | Status |
|---|---|---|
| Datum, blankett och årets belopp | `references/inkomstar-ÅÅÅÅ.md` | klar för 2025 |
| Vilka händelser som ska deklareras | `references/handelser.md` | klar |
| Genomsnittsmetoden och avgifter | `references/genomsnittsmetoden.md` | klar |
| Så fylls K4 avsnitt D i | `references/k4-avsnitt-d.md` | klar |
| Skattesatser och kvotering | `references/belopp-och-skattesatser.md` | klar |
| Vad som ska sparas | `references/underlag.md` | klar |

Skillen täcker privatpersoner som har bott i Sverige hela året och som redovisar kryptovaluta som kapitalplacering i Inkomstdeklaration 1.

Utanför skillen. Säg det och hänvisa vidare. Ge inte råd om det.

- Näringsverksamhet, utåtriktad växlingsverksamhet och mining som uppfyller kriterierna för näringsverksamhet.
- NFT. Skatteverket har en egen sida, och genomsnittsmetoden ska normalt inte användas.
- Derivat, CFD och certifikat, utöver den korta hänvisningen i `handelser.md`. Ett certifikat är inte samma sak som att äga kryptovalutan.
- Investeringssparkonto och kapitalförsäkring. Den här skillen gäller bilaga K4.
- Den som inte har bott i Sverige hela året, dödsbon och fåmansföretag.
- Deklarationen i övrigt. Använd skillen inkomstdeklaration om den finns.

## Tillsammans med inkomstdeklaration

- Användaren bara ska deklarera krypto, eller bara frågar om kryptoskatt: använd den här skillen. Läs inte inkomstdeklarationens områden som är under arbete.
- Hela deklarationen gås igenom med skillen inkomstdeklaration: den skillen äger arbetsgången. Använd den här skillen som fördjupning för kryptoraderna på K4 avsnitt D, för löpande kapitalinkomst av krypto vid punkt 7.2 och för fiatvaluta som bytts mot krypto på K4 avsnitt C. Lämna tillbaka en tabell med belopp, punkt och underlag. Fyll inte i andra punkter här.
- Mining som hobby, eller lön i kryptovaluta: kapitaldelen räknas här. Inkomsten i tjänst räknas i inkomstdeklaration (`references/tjanst.md`, punkt 1.1 eller bilaga T2). Omkostnadsbeloppet i kapital är det marknadsvärde som tas upp där.

## Arbetsgång

### Steg 1 – Inkomstår och avgränsning

1. Bekräfta inkomstår (normalt förra kalenderåret), att användaren är privatperson och har bott i Sverige hela året. Läs `references/inkomstar-ÅÅÅÅ.md`. Finns ingen årsfil: säg att skillen inte är uppdaterad och hämta datum och belopp på skatteverket.se innan du räknar.
2. Har sista dagen passerat, eller är deklarationen redan inlämnad: följ avsnittet Sen eller ändrad deklaration i skillen inkomstdeklaration om den finns. Annars hänvisa till Skatteverkets sidor om sen deklaration och omprövning. Du skickar ändå inte in något.
3. Fråga hur användaren vill arbeta: en lista att fylla i själv, eller att du fyller i bekräftade belopp i e-tjänsten. I båda fallen skriver användaren under själv.

### Steg 2 – Samla transaktioner

Be om export från varje växlare och plånbok som använts, även sådant som inte rör årets försäljningar. Genomsnittet bygger på hela historiken. Läs `references/underlag.md`.

Behövs för varje affär: tidpunkt, kryptovaluta, antal, vad som betalades eller togs emot, avgift, och i vilken valuta. Saknas ingående innehav och dess omkostnadsbelopp: stanna för den kryptovalutan.

### Steg 3 – Klassa händelser

Läs `references/handelser.md`. Gå igenom händelserna med användaren. En flytt mellan egna plånböcker är ingen avyttring. En växling mellan två kryptovalutor är både en försäljning och ett köp.

Särskilj det som ska till K4 avsnitt D, det som är löpande kapitalinkomst (punkt 7.2), det som är tjänst (mining, lön) och det som ska vänta eftersom Skatteverket inte har gett ett generellt svar.

### Steg 4 – Räkna genomsnitt

Läs `references/genomsnittsmetoden.md` och `references/belopp-och-skattesatser.md`. Räkna en kryptovaluta i taget, i tidsordning, över alla plånböcker. Visa poolen efter varje avyttring under året: antal kvar, omkostnadsbelopp kvar, försäljningspris, vinst eller förlust.

Kontrollera mot hjälpblanketten SKV 2198 eller Skatteverkets beräkningshjälp när antalet affärer är litet. Hjälpblanketten lämnas inte in.

### Steg 5 – Förbered K4 avsnitt D

Läs `references/k4-avsnitt-d.md`. Summera vinster för sig och förluster för sig, per kryptovaluta. För över inte 70 procent. E-tjänsten för beloppen vidare själv. På papper förs summa vinst till punkt 7.5 och summa förlust till punkt 8.4, ihop med det som redan står där.

### Steg 6 – Sammanställ och få bekräftelse

Visa tabellen innan något fylls i:

| Kryptovaluta | Antal | Försäljningspris | Omkostnadsbelopp | Vinst | Förlust | Punkt | Underlag |
|---|---|---|---|---|---|---|---|

Ta med punkt 7.2 (ränta, staking av ether, annan löpande avkastning) och K4 avsnitt C (fiatvaluta) på egna rader. Låt användaren bekräfta varje rad. Säg vilka händelser som lämnats utanför och varför.

### Steg 7 – Fyll i, granska, användaren skriver under

Fyll bara i belopp som användaren har bekräftat.

- **Lista:** ge beteckning, antal, försäljningspris, omkostnadsbelopp, vinst och förlust, och säg vart summan ska. Påminn om förifyllda belopp vid punkt 7.5 och 8.4.
- **E-tjänst:** användaren loggar in själv. Bilagan heter K4 – Övriga värdepapper, andra tillgångar (kapitalplaceringar t.ex. råvaror, kryptovalutor) m.m. Kontrollera efter varje rad att vinsten eller förlusten stämmer. Ändra inte kontaktuppgifter eller bankkonto.

Stanna före Skriv under. Användaren granskar skatteuträkningen och skriver under själv. E-tjänsten visar en kvittens.

### Steg 8 – Spara underlag

Påminn om vad som ska sparas och hur länge, enligt `references/underlag.md` och årsfilen.

## Källor

- Skatteverket: [Kryptovalutor](https://www.skatteverket.se/privat/skatter/vardepapper/andratillgangar/kryptovalutor.4.15532c7b1442f256bae11b60.html)
- Skatteverket: [Andra tillgångar](https://www.skatteverket.se/privat/skatter/vardepapper/andratillgangar.4.233f91f71260075abe8800099480.html)
- Skatteverket: [Särskilt om kryptotillgångar i inkomstslaget kapital](https://www4.skatteverket.se/rattsligvagledning/edition/2025.1/409288.html) (utgåva 2025.1)
- Skatteverket: [K4, SKV 2104](https://www.skatteverket.se/privat/etjansterochblanketter/blanketterbroschyrer/blanketter/info/2104.4.39f16f103821c58f680006244.html)
- [Inkomstskattelag (1999:1229)](https://www.riksdagen.se/sv/dokument-och-lagar/dokument/svensk-forfattningssamling/inkomstskattelag-19991229_sfs-1999-1229/)
