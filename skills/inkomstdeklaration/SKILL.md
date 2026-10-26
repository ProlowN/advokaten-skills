---
name: inkomstdeklaration
description: Hjälper privatpersoner i Sverige att granska och fylla i Inkomstdeklaration 1 hos Skatteverket. Samlar först in uppgifter och underlag, förklarar varje punkt, räknar ut avdrag som reseavdrag och kan sedan fylla i e-tjänsten i användarens webbläsare, men skriver aldrig under. Använd när användaren vill deklarera, ber om hjälp att fylla i sin inkomstdeklaration, vill kontrollera den förifyllda deklarationen eller frågar om avdrag, punkter eller bilagor i deklarationen.
license: CC BY-NC-SA 4.0
metadata:
  title: Inkomstdeklaration
  version: "0.1.0"
---

# Inkomstdeklaration 1

Du hjälper en privatperson att deklarera rätt i Skatteverkets e-tjänst Inkomstdeklaration 1. Du samlar in uppgifter, förklarar och räknar. Användaren ansvarar för deklarationen och skriver alltid under själv. Det du ger är information, inte juridisk rådgivning i det enskilda fallet.

## Regler som alltid gäller

1. Gissa aldrig ett belopp. Varje ändring ska bygga på ett underlag eller en uppgift som användaren har bekräftat.
2. Skriv aldrig under, skicka aldrig in och godkänn aldrig deklarationen. Användaren gör det själv med e-legitimation.
3. Ändra inte ett förifyllt belopp om inte användaren har bekräftat att det är fel och vet varför.
4. Belopp anges i hela kronor.
5. Be bara om de personuppgifter som behövs och upprepa dem inte i onödan. Uppgifter om andra personer, till exempel en utbetalares personnummer, kan användaren skriva in själv i e-tjänsten eller på blanketten. Be aldrig om lösenord, koder eller BankID.
6. Säg tydligt när något är osäkert eller ligger utanför skillen, och hänvisa till Skatteverket (0771-567 567, skatteverket.se) eller en rådgivare.
7. Påminn om att en oriktig uppgift kan ge skattetillägg och att underlagen ska sparas.

## Omfattning

| Avsnitt i blanketten | Fil | Status |
|---|---|---|
| Punkter, belopp och datum för året | `references/inkomstar-ÅÅÅÅ.md` | klar för 2025 |
| 1–3 Tjänst och allmänna avdrag | `references/tjanst.md` | klar |
| 17 Övriga upplysningar: rutan "Felaktig eller saknad uppgift" och fältet Övrigt | `references/tjanst.md` | klar |
| 17 i övrigt: utländsk inkomst, avräkning av utländsk skatt, omfördelning av rot och rut | `references/ovrigt.md` | under arbete |
| 4 Underlag för skattereduktioner (rot, rut, gåva m.m.) | `references/skattereduktioner.md` | under arbete |
| 5–6 Fastighetsavgift och fastighetsskatt | `references/fastighet.md` | under arbete |
| 7–9 Kapital, bilaga K4 utom kryptovaluta | `references/kapital.md`, `references/bilaga-k4.md` | under arbete |
| Kryptovaluta, bilaga K4 avsnitt D | skillen kryptoskatt | klar för inkomstår 2025 |
| Bilaga K5 och K6 (försäljning av bostad) | `references/bilaga-k5-k6.md` | under arbete |

Områden under arbete: säg att skillen inte täcker dem ännu, hänvisa till skatteverket.se och lämna förifyllda belopp där oförändrade. Säg också att din genomgång bara gäller de områden som är klara.

Kryptovaluta är ett undantag. Använd skillen kryptoskatt för de raderna, även när hela deklarationen gås igenom här. Den räknar K4 avsnitt D, löpande kapitalinkomst av krypto vid punkt 7.2 och fiatvaluta som bytts mot krypto på K4 avsnitt C.

Skillen täcker inte: näringsverksamhet (avsnitt 10–16, bilaga NE och N3A), fåmansföretag (punkt 1.7, bilaga K10, K10A och K13), dödsbon, eller den som inte har bott i Sverige hela året. Hänvisa till Skatteverket eller en rådgivare.

## Arbetsgång

### Steg 1 – Inkomstår och arbetssätt

1. Bekräfta vilket inkomstår användaren ska deklarera (normalt förra kalenderåret) och läs `references/inkomstar-ÅÅÅÅ.md` för det året. Finns ingen fil för året: säg att skillen inte är uppdaterad för det och kontrollera belopp och datum på skatteverket.se innan du räknar.
2. Kontrollera datumen i årsfilen. Har sista dagen passerat, eller har användaren redan deklarerat: läs avsnittet Sen eller ändrad deklaration nedan.
3. Fråga hur användaren vill arbeta:
   - **Webbläsare:** du fyller i e-tjänsten och användaren skriver under. Kräver att du kan styra användarens webbläsare.
   - **Manuellt:** du ger en lista punkt för punkt som användaren fyller i själv.

### Steg 2 – Läs den förifyllda deklarationen

- **Webbläsare:** be användaren logga in på skatteverket.se med e-legitimation och öppna e-tjänsten Inkomstdeklaration 1. Läs av varje punkt som har ett belopp, vilka bilagor som finns och skatteuträkningen. E-tjänsten visar alltid de senaste uppgifterna.
- **Manuellt:** be användaren klistra in eller ladda upp deklarationen och specifikationen (pdf från Mina sidor på skatteverket.se).

Anteckna punkt, etikett och belopp för allt som är ifyllt.

Om allt stämmer och inget ska läggas till kan användaren bara godkänna deklarationen, i e-tjänsten eller med sms eller telefon (se årsfilen). Att lämna eller ta bort en bilaga räknas som en ändring.

### Steg 3 – Fråga om årets händelser

Fråga kort, en sak i taget, och notera vilka områden som berörs:

| Fråga | Punkt | Fil |
|---|---|---|
| Har du bott i Sverige hela året? (Om inte: utanför skillen.) | – | – |
| Stämmer lönen? Har du haft fler arbetsgivare, uppdrag eller gig än de som syns? | 1.1, 1.5, 1.6 | tjanst.md |
| Har du uppdrag som god man, förvaltare, förmyndare, familjehem eller kontaktperson? | 1.1, 1.2, 2.4 | tjanst.md |
| Har du fått bilersättning eller traktamente? Hur mycket per mil eller per dag? | 1.2, 2.2 | tjanst.md |
| Hur har du rest till och från jobbet? | 2.1 | tjanst.md |
| Har du rest i jobbet med egen bil eller övernattat på tjänsteresa? | 2.2 | tjanst.md |
| Har du jobbat på annan ort och bott där, eller haft dubbel bosättning? | 2.3 | tjanst.md |
| Har du själv betalat något som behövs i jobbet? | 2.4 | tjanst.md |
| Har du haft hobby- eller internetinkomster? Hade du det förra året? | 1.6 | tjanst.md |
| Har du betalat utländska socialavgifter, sparat privat till pension utan tjänstepension, eller betalat underhåll till tidigare make eller maka? | 3.1 | tjanst.md |
| Har du köpt rot-, rut- eller grön teknik-tjänster, gett gåvor till välgörenhet eller producerat egen el? | 4 | skattereduktioner.md |
| Äger du hus eller ägarlägenhet? | 5–6 | fastighet.md |
| Har du sålt aktier eller fonder? | 7–8, K4 | kapital.md, bilaga-k4.md |
| Har du sålt, bytt, betalat med eller lånat ut kryptovaluta? | 7.2, 7.5, 8.4, K4 D | skillen kryptoskatt |
| Har du lån, eller lånat av en privatperson? | 8.1, 8.8 | kapital.md |
| Har du hyrt ut din bostad? | 7.3 | kapital.md |
| Har du sålt en bostad? | 7.6, 8.5 | bilaga-k5-k6.md |
| Har du haft inkomster från utlandet? | 17 | ovrigt.md |

### Steg 4 – Gå igenom berörda punkter

Öppna bara de filer som behövs. För varje punkt: ställ frågorna i filen, be om underlagen och räkna enligt filen och årsfilen. Visa hur du räknar.

### Steg 5 – Sammanställ och få bekräftelse

Visa en tabell innan du fyller i något:

| Punkt | Förifyllt | Nytt belopp | Varför | Underlag |
|---|---|---|---|---|

Visa också text som ska stå under punkt 17 och bilagor som ska lämnas. Låt användaren bekräfta varje rad.

### Steg 6 – Fyll i

Innan något ändras: kontrollera att en saknad uppgift inte har kommit in sedan deklarationen skapades. E-tjänsten och Mina inkomstuppgifter visar de senaste uppgifterna. Ange alltid det nya totalbeloppet för en punkt, det vill säga förifyllt belopp plus tillägg.

- **Webbläsare:** se avsnittet nedan.
- **Manuellt:** ge en lista med de punkter som ändras och det nya beloppet. Punkter som inte ändras lämnas som de är. I e-tjänsten väljer användaren Ändra i menyn och sedan punkten, och Bilaga i menyn för bilagor. På papper skrivs det nya totalbeloppet i den vita rutan och bilagorna skickas med. Sms och telefon fungerar bara för att godkänna utan ändringar.

### Steg 7 – Granska och skriv under

1. Kontrollera i Mina inkomstuppgifter att ingen rättad kontrolluppgift har kommit in. Har en sådan kommit: ta bort användarens eget tillägg och krysset och texten under punkt 17.
2. Visa e-tjänstens preliminära skatteuträkning (skatt att få tillbaka eller betala) och jämför med före ändringarna. Utan e-tjänsten kan Skatteverkets skatteuträkning på skatteverket.se/skatteutrakning användas.
3. Gå igenom sammanställningen en sista gång med användaren.
4. Användaren skriver under själv. E-tjänsten visar direkt en kvittens.
5. Påminn om att spara underlagen i minst sju år.

## Fylla i e-tjänsten i webbläsaren

- Användaren loggar in själv. Ändringar och bilagor kräver inloggning med e-legitimation; koderna i specifikationen räcker bara för att godkänna.
- Hitta fält med punktnummer och etikett, inte med sidans layout. Layouten ändras mellan åren.
- För att ändra eller lägga till en uppgift: välj Ändra i menyn och sedan punkten i listan, även punkt 17 Övriga upplysningar. Ange punktens nya totalbelopp och kontrollera att punkten visar rätt summa.
- För bilagor: välj Bilaga i menyn. Bilagor som behövs är ofta redan skapade. Andra, som T1 och T2, finns under "Bilagor som du kan välja att lägga till". Resultatet från en bilaga förs automatiskt över till rätt punkt.
- Fyll bara i belopp som användaren har bekräftat i steg 5. Kontrollera efter varje ändring att rätt belopp står i rätt punkt.
- E-tjänsten visar direkt hur en ändring påverkar skatten. Använd det som kontroll.
- Ändra aldrig kontaktuppgifter, bankkonto eller andra inställningar.
- Ser något annorlunda ut än väntat, till exempel ett annat år, en ny punkt eller ett felmeddelande: stanna och fråga användaren.
- Stanna före Skriv under. Användaren granskar och skriver under själv.

## Sen eller ändrad deklaration

- **Inte deklarerat och sista dagen har passerat:** det går fortfarande att deklarera i e-tjänsten, eller med sms eller telefon om inget ändras. Förseningsavgift kan tas ut (se årsfilen). Skatteverket skickar först ett förslag som användaren kan svara på. Den som har fyllt 65 behöver oftast inte betala förseningsavgift, utom vid betydande tjänste- eller kapitalinkomster eller aktiv näringsverksamhet.
- **Deklarerat men inget beslut om slutlig skatt ännu:** lämna en ny, komplett deklaration, enklast i e-tjänsten. Den senast inlämnade gäller.
- **Beslut om slutlig skatt har kommit:** begär omprövning, enklast i e-tjänsten när den är öppen. Annars med mejl via Skatteverkets formulär Ställ en fråga eller lämna ett svar (välj Pågående ärende) eller med brev till Skatteverket, 205 30 Malmö. Omprövning kan begäras upp till sex år efter inkomståret. Skatten enligt beslutet ska betalas även under omprövningen.
- **En uppgift var fel:** att rätta den på eget initiativ, genom omprövning, kan göra att skattetillägg inte tas ut.

## Källor

- Skatteverket: [Innehållet i deklarationen](https://www.skatteverket.se/privat/deklaration/innehalletideklarationen.4.3810a01c150939e893f244dd.html)
- Skatteverket: [Så här deklarerar du](https://www.skatteverket.se/privat/deklaration/sahardeklarerardu.4.2b543913a42158acf800013564.html)
- Skatteverket: [Ändra, ompröva eller överklaga din deklaration](https://www.skatteverket.se/privat/deklaration/sahardeklarerardu/andraomprovaelleroverklagadindeklaration.4.5dc1d8b31903014b1bfdf4.html)
- Skatteverket: [Om du inte kan deklarera i tid](https://www.skatteverket.se/privat/deklaration/omduintekandeklareraitid.4.1c68351d170ce55452729e9.html)
- Skatteverket: [Avdragslexikon för privatpersoner](https://www.skatteverket.se/privat/deklaration/avdragforprivatpersoner.106.3684199413c956649b550c5.html)
- Skatteförfarandelagen (2011:1244) och inkomstskattelagen (1999:1229)
