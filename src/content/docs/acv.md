---
Title: 9. Växelspänning
weight: 9
---

# Växelspänning

![Sinuskurva](/sinus.png)

Växelspänning ändrar riktning och storlek hela tiden. Bilden ovanför visar hur spänningen går från 0V till + och sedan tillbaka ner till 0V och till -.
Kurvan som syns i bilden heter sinuskurva. Växelspänning har altså inte + och - på samma ställe hela tiden. + och - byter hela tiden platts det kallas att polariteten ändras.

## AC
Ofta kallas växelspänning/växelström för AC vilket betyder Alternating Current.

## DC
Ofta kallas likspänningen/likström (när det finns ett + och ett -) för DC vilket betyder Direct Current.

## Toppvärde
Toppvärdet är det som är högst upp på sinuskurvan.  
{{< katex >}} û {{< /katex >}} = Toppvärde  
![Sinuskurvamedtippvärde](/sinustop.png)

## Effektivvärde
Effektivvärdet är hur stor spänningen är i medel.
Näs polariteten är tvärt om så ändrar det inte riktningen på effektivvärdet.
Detta beror på att effektivvärdet beskriver hur stor effekten är inte vilket håll den kommer från.
I en DC krets så finns bara effektivärdet. Det är effektivvärdet vi använder när vi räknar med tillexmepel Ohms-lag.
  
{{< katex >}} U {{< /katex >}} = Effektivvärde  
![Sinuskurvamedtippvärde](/sinuseffektiv.png)

## Samband

Toppvärdet är alltid störren än effektivvärdet eftersom effektivvärdet är medelspänningen för strömmen/spänningen.
Effektivvärdet är det samma som spänningen i en DC krets. Så in en DC krets så är toppvärdet och effektivvärdet samma.

### Exempel

Effektivvärdet är alltid lägre än toppvärdet.

Toppvärdet är alltid större än effektivvärdet.

## Beräkningar
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
|{{< katex >}} û = 325V  {{< /katex >}}    | 

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
| Ström (Effektivvärde) | I                  | Ampere      | A                |
| Ström (Toppvärde)       | î               | Ampere      | A                |
| Spänning (Effektivvärde)     | U                  | Volt        | V                |
| Spänning (Toppvärde) | û | Volt     | V                | 
| Resistans     | R                  | Ohm         | Ω                |
| Längd        | l                  | Meter       | m                |
| Tvärsnittsarea | A                | Kvadratmillimeter | mm²| 
| Resistivitet | {{< katex >}}\rho{{< /katex >}} | Ohm per meter per kvadratmillimeter | Ohm/m/mm² | 
| Effekt       | P                  | Watt        | W                |
| Periodtid | {{< katex >}} t {{< /katex >}}  | Sekunder     | s                | 
| Frekvens | {{< katex >}} f {{< /katex >}}                  | Hertz     | Hz                | 

