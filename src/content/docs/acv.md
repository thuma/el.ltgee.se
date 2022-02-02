---
Title: 9. Växelspänning
weight: 9
---

# Växelspänning

![Sinuskurva](/sinus.png)

Växelspänning ändrar riktning och storlek hela tiden. Bilden ovanför visar hur spänningen går från 0V till + och sedan tillbaka ner till 0V och till -.
Kurvan som syns i bilden heter sinuskurva. Växelspänning har altså inte + och - på samma ställe hela tiden. + och - byter hela tiden platts det kallas att polariteten ändras.

## Toppvärde & Effektivvärde
![Sinuskurvamedtippvärde](/sinustop.png)

Toppvärdet är det som är högst upp på sinuskurvan.
{{< katex >}} û {{< /katex >}} = Toppvärde  

Spänningen U som är den spänning som en DC krets har, där det är samma spänningn hela tiden. Det är alltså samma effekt hela tiden därför kallas detta värde Effektivvärde.

### Exempel

Effektivvärdet är alltid lägre än toppvärdet.

Toppvärdet är alltid större än effektivvärdet.

### Formel
För att räkna ut toppvärdet när du har effektivvärdet använder du följande formel.  
{{< katex >}} û = U * \sqrt[]{2} {{< /katex >}}

### Beräkna effektivvärde från toppvärde:

| Data       |
| ---------- |
| {{< katex >}} û = 15V  {{< /katex >}}     | 

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} U = \frac{û}{\sqrt[]{2}} {{< /katex >}} |
| Uträkning | {{< katex >}} U = \frac{15V}{\sqrt[]{2}} {{< /katex >}}  |
| Resultat  | {{< katex >}} U = 10.6V {{< /katex >}}   |

| Svar      |
| ---------- |
|{{< katex >}} û = 15V  {{< /katex >}}    | 
|{{< katex >}} U = 10.6V {{< /katex >}}   |

### Beräkna toppvärde från effektivvärde:

| Data       |
| ---------- |
| {{< katex >}} U = 230V  {{< /katex >}}     | 

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} û = U * \sqrt[]{2} {{< /katex >}} |
| Uträkning | {{< katex >}} û = 230V * \sqrt[]{2} {{< /katex >}}  |
| Resultat  | {{< katex >}} û = 325V {{< /katex >}}   |

| Svar      |
| ---------- |
|{{< katex >}} U = 230V {{< /katex >}}   |
|{{< katex >}} û = 15V  {{< /katex >}}    | 

## Periodtid & Frekvens
![Sinuskurvamedperiodtid](/sinusperiod.png)

En period växelspänning är från att spänningen börjar öka från 0V och går till sitt max värde, som kallas för toppvärde, 
till sitt minnsta värde, som kallas för bottenvärde, och upp till 0V igen. 
Periodtid är hur lång tid det tar för spänningen att gå hela vägen upp ner och upp igen.

Frekvens är hur många gånger något händer per sekund. Det mäts i enheten Hertz(Hz).

### Ordet period
Ordet period är samma som en period är i hockey, innebandy, etc. Alltså en omgång.
I boxning heter det rond alltså rund/varv en elektrisk peroiod är också ett varv för en enkel generator. 

### Exempel

Om frekvensen minskar så ökar periodtiden.

Om frekvensen ökar så minskar persiodtiden.

Om periodtiden minskar så ökar frekvensen.

Om periodtiden ökar så minskar frekvensen.

### Formel
För att räkna ut frekvensen så gäller följande formel:  
{{< katex >}} f = \frac{1}{t} {{< /katex >}}

### Beräkna frekvensen från periodtid:

| Data       |
| ---------- |
| {{< katex >}} t = 10ms  {{< /katex >}}     | 

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} f = \frac{1}{t} {{< /katex >}} |
| Uträkning | {{< katex >}} f = \frac{1}{0.01s} {{< /katex >}}  |
| Resultat  | {{< katex >}} f = 100Hz {{< /katex >}}   |

| Svar      |
| ---------- |
| {{< katex >}} t = 10ms  {{< /katex >}}     | 
| {{< katex >}} f = 100Hz {{< /katex >}}   |

### Beräkna periodtid från frekvensen:

| Data       |
| ---------- |
| {{< katex >}} f = 50Hz  {{< /katex >}}     | 

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} t = \frac{1}{f} {{< /katex >}} |
| Uträkning | {{< katex >}} t = \frac{1}{50Hz} {{< /katex >}}  |
| Resultat  | {{< katex >}} f = 0.02s {{< /katex >}}   |

| Svar      |
| ---------- |
| {{< katex >}} f = 50Hz {{< /katex >}}   |
| {{< katex >}} t = 20ms  {{< /katex >}}     | 

## Frågor

Vad är störst av effektivvärde och toppvärde?

Vad är minsta av toppvärde och effektivvärde?

Vad händer med frekvensen om periodtiden ökar?

Vad händer med frekvensen om persiodtiden minskar?

Vad händer med periodtiden om frekvensen ökar?

Vad händer med periodtiden om frekvensen minskar?


## Storhets och Enhetstabell

| Storhet      | Beteckning | Enhet       | Beteckning |
| ------------ | ------------------ | ----------- | ---------------- |
| Ström        | I                  | Ampere      | A                |
| Spänning (Effektivvärde)     | U                  | Volt        | V                |
| Resistor     | R                  | Ohm         | Ω                |
| Längd        | l                  | Meter       | m                |
| Tvärsnittsarea | A                | Kvadratmillimeter | mm²| 
| Resistivitet | {{< katex >}}\rho{{< /katex >}} | Ohm per meter per kvadratmillimeter | Ohm/m/mm² | 
| Effekt       | P                  | Watt        | W                |
| Verkninsgrad | 𝝶                  | Procent / Faktor     | % / ingen                | 
| Spänning (Toppvärde) | û | Volt     | V                | 
| Periodtid | {{< katex >}} t {{< /katex >}}  | Sekunder     | s                | 
| Frekvens | {{< katex >}} f {{< /katex >}}                  | Hertz     | Hz                | 

