---
Title: 7. Ledningsresistans
weight: 7
---
# Ledningsresistans

Ledare leder ström bra, men alla ledare har lite [resistans](/docs/el/). När strömmen rör sig i en ledare så kommer den alltså att bromsas ner. Det finns fyra saker som påverkar resistansen i ledaren:

 1. Längd 
 2. Tvärsnittsarean (Tjocklek)
 3. Material
 4. Temperatur

## Längd
Ju längre kabeln är desto mer kommer den att bromsas eftersom elektronerna måste röra sig längre. Det är samma princip som när du ska gǻ eller cykla långt. Det är lättare att gå en kort sträcka och jobbigare att gå en lång sträcka.

## Tvärsnittsarean (Tjocklek)
Om kabeln är tjockare, har större tvärsnittsarea, så kommer resistansen att minska eftersom elektronerna har mer plats att rör sig och inte behöver träggas som i en smal ledare. Det är samma princip som när du står i kö och det bara finns en kassa på McDonalds. Då blir det en 
lång kö som går sakta. Men om det är många kassor öppna så blir det många köer då får fler mat snabbare. Då kan det flöda igenom fler personer snabbare. På samma sätt så kan strömmen komma igenom snabbare när det är större tvärsnittsarea eftersom flera elektroner kan komma igenom brevid varandra i stället för att så i en lång kö.

## Material
Olika meterial är olika bra på att leda koppar är bättre än guld t.ex. och Silver är bättre än koppar. Det beror på att atomerna i de olika materialen har olika antal elektroner runt sig som kan hoppa vidare till nästa atom olika lätt. I [tabellen](#beräkningar) längre ner kan du se olika ledares resistans per meter.

## Temperatur
Högre temperatur ger högre resistans och lägre temperatur ger lägre resistans. När ett material har högre temperatur så är atomerna längre ifrån varandra det gör att det är långt för elektroner att hoppa mellan atomerna. Dessa långa hopp gör att resistansen ökar när temperaturen ökar. 

## Ordförklaringar
### Tvärsnittsarea
Tvärsnittsarea på kablar är hur många mm² som ledaren har om du sågar av den och mäter den från kortsidan. Detta blir alltså ett mått på tjockleken på ledaren. En vanlig ledning i ett hus för lampor eller elluttag brukar vara 1,5 mm². Tvärsnitt betyder snitt på tvären. Ordet snitt är när du gör ett snitt med kniven i en kycklingfilé då kan du kolla på hur stor yta som det blir på tvären genom kycklingfilén. Även kycklingfilé med stor tvärsnittsarea har lägre resistans än en kycklingfié med liten area. 

### Ledning
För att överföra elektrisk ström så använder vi ledningar. Ledaren i en kabel är den delen som är av metall oftast koppar eller aluminium. Strömmen följer ledaren hela vägen från spänningskällan till belastningen och tillbaka till spänningskällan. Det som är runt ledare som oftast är plast eller gummi kallas för isolator.
Det är samma ord:

 * Företagsledning - Leder företaget framåt och vara den som alla som jobbar följer.
 * Att vara i ledningen - Att vara längst fram i ett sprinterlopp och vara den som alla följer.

### Isolator
Isolator betyder att den isolerar något. I elläran är isolatorn något som isolerar så att strömmen inte kan ta sig den vägen. Det är samma betydelse som:

 * Värmeisolering - Att hålla isär värme och kyla inne och ute ur ett hus.
 * Isolercell - Att hålla en person isär från alla andra genom att sätta denna i en egen cell.
 * Social isolering - Att hållas isär från andra människor genom att inte prata med dem till exempel.
 
## Exempel

 * En lång ledare har högre resistans än en kortare.
 * En kort ledare har lägre resistans än en längre.
 * En tjock ledare, som alltså har stor tvärsnittsarea i mm², har en lägre resistans än en tunn ledare.
 * En tunn ledare, som alltså har liten tvärsnittsarea i mm², har en högre resistans än en tjock ledare.
 * Ledare av koppar har lägre resistans än en ledare av stål.
 * Ledare av bly har högre resistans än en ledare av koppar.
 * En varm ledare har högre resistans än en kall ledare.
 * En kall ledare har en längre resistans än en varm ledare.

## Beräkningar
För att räkna ut ledningsressistansen i rumstemperatur så används följande formel:  
{{< katex >}}R_l =  \frac{\rho*l}{A}{{< /katex >}}

{{< katex >}}l{{< /katex >}} beskriver hur lång kabeln är i meter.

{{< katex >}}A{{< /katex >}}  är arean på ledaren och det är så man mäter hur tjock en ledare är. Tänk dig att du sågar av en sladd, då kan du se koppartrådarna inne i kabeln. Det är hur många mm² som dessa är som beskriver hur tjock kabeln är.

{{< katex >}}\rho{{< /katex >}} kallas Rho och är hur stor resistans per meter som respektive material har vid en tjocklek på kabeln på 1 mm². Detta kallas för resistivitet.

I denna tabell ser du olika materials resistivitet

| Material | Ohm/m/mm² |
| -------- | --------- |
| Silver   | 0,0159    |
| Koppar   | 0,01678   |
| Guld     | 0.235     |
| Aluminium| 0,0265    |
| Zink     | 0,0592    |
| Nickel   | 0,0684    |
| Järn     | 0,097     |
| Tenn     | 0,101     |
| Stål     | 0,16      |
| Bly      | 0,206     |

### Ledningsresistansen

| Data       |
| ---------- |
| {{< katex >}} \rho = Koppar {{< /katex >}}     | 
| {{< katex >}} l = 100m {{< /katex >}}   |
| {{< katex >}} A = 2mm² {{< /katex >}}   | 

| Steg      | Uträkning av totala resistansen |
| --------- | ------------ |
| Formel    | {{< katex >}}R_l =  \frac{\rho*l}{A}{{< /katex >}}   |
| Uträkning | {{< katex >}}R_l =  \frac{0,01678 * 100m}{2mm²}{{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 839 m\Omega {{< /katex >}} |

| Svar       |
| ---------- |
| {{< katex >}} \rho = Koppar {{< /katex >}}     | 
| {{< katex >}} l = 100m {{< /katex >}}   |
| {{< katex >}} A = 2mm² {{< /katex >}}   | 
| {{< katex >}} R_{tot} = 839 m\Omega {{< /katex >}}   | 

### Längden
| Data       |
| ---------- |
| {{< katex >}} \rho = Koppar {{< /katex >}}     | 
| {{< katex >}} R_{tot} = 1678 m\Omega {{< /katex >}}   | 
| {{< katex >}} A = 4mm² {{< /katex >}}   | 

| Steg      | Uträkning av totala resistansen |
| --------- | ------------ |
| Formel    | {{< katex >}}R_l =  \frac{\rho*l}{A}{{< /katex >}}   |
| Uträkning | {{< katex >}}1678 m\Omega =  \frac{0,01678 * l}{4mm²}{{< /katex >}} |
| Uträkning | {{< katex >}}1678 m\Omega * 4mm² = 0,01678 * l{{< /katex >}} |
| Uträkning | {{< katex >}}\frac{1678 m\Omega * 4mm²}{0,01678} = l {{< /katex >}} |
| Resultat  | {{< katex >}} l = 400 m {{< /katex >}} |

| Svar       |
| ---------- |
| {{< katex >}} \rho = Koppar {{< /katex >}}     | 
| {{< katex >}} l = 100m {{< /katex >}}   |
| {{< katex >}} A = 2mm² {{< /katex >}}   | 
| {{< katex >}} R_{tot} = 839 m\Omega {{< /katex >}}   | 

## Frågor

Vad har lägst resistans av en kort och en lång ledare?

Vad har högst resistans av en lång och en kort ledare?

Vad har lägst ressistans av en tjock och en tunn ledare?

Vad har högst resistans av en tunn och en tjock ledare?

Vad har lägst ressistans av en koppar och en järn ledare?

Vad har högst resistans av en koppar och en silver ledare?

Vad har lägst ressistans av en varm och en kall ledare?


## Sorheter och enheter
| Storhet      | Beteckning | Enhet       | Beteckning |
| ------------ | ------------------ | ----------- | ---------------- |
| Ström        | I                  | Ampere      | A                |
| Spänning     | U                  | Volt        | V                |
| Resistans    | R                  | Ohm         | Ω                |
| Effekt       | P                  | Watt        | W                |
| Längd        | l                  | Meter       | m                |
| Tvärsnittsarea | A                | Kvadratmillimeter | mm²| 
| Resistivitet | {{< katex >}}\rho{{< /katex >}} | Ohm per meter per kvadratmillimeter | Ohm/m/mm² | 


