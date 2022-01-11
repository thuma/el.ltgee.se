---
title: "4. Parallellkrets"
---
# Parallellkrets

I parallellkretser kopplas de komponenter som ska användas på varandra, eller parallellt. De kallas också för parallellkopplingar eftersom de kopplas så. I en paralellkrets så får strömmen fler vägar att ta sig fram. Eftersom det finns fler vägar för strömmen så går det mer ström ju fler komponenter som koppas in. Mer ström betyder då att den totala resistansen måste ha blivit mindre.
Den totala resistansen blir alltså mindre än de olika delresistanserna i en parallellkoppling. En bra minnesregel är därför att totalresistansen alltid blir mindre än den minsta resistansen i en
parallellkoppling.

## Ordet parallell
För att komma ihåg ordet vad ordet parallell betyder så är det samma ord som du använder i andra lägen så som:
 * Parallella universum
 * Parallella linjer
 * Parallellslalom
Ordet paralell betyder alltså bara att något ligger vid sidan av varandra. Parallella saker korsar inte varandra, när du har dina skidor paralellt så går det bra men korsar du dem så ramlar du direkt.

## Samband
### Spänningen
I en paralellkrets är alla komponeneter direkt kopplade till spänningskällan och har därför samma spänning. Så spänningn för komponent 1,2 och 3 har samma spänning i en parallellkrets.
{{< katex >}}U = U_1 = U_2 = U_3...{{< /katex >}} 

### Strömmen
I en parallellkrets så finns det flera olika strömmar eftersom strömmen kan ta flera olika vägar. Strömmen som kommer från spänningskällan är så summan av alla strömmarna.
{{< katex >}}I = I_1 + 1_2 + I_3...{{< /katex >}}

### Resistansen
I en paralellkrets så minskar resistasen ju fler komponenter som kopplas in. Detta beror på att att strömmen får flera vägar att gå. Eftersom strömmen har flera vägar att gå så kommer den totala strömmen att öka utan att spänningen ändras. Då säger Ohms lag att resistansen har minskat. Alltså fler komponenter innebär lägre resistans. Det finns olika sätt att räka ut resistansen antingen genom att räkna ut den totala strämmen och räkna ut resistansen med hjälp av Ohms-lag eller genom att använda någon av dessa formler:

#### Basform
{{< katex >}}\frac{1}{R_{tot}} = \frac{1}{R_1} + \frac{1}{R_1} + \frac{1}{R_3} + ...{{< /katex >}}

#### Beräkningsform
{{< katex >}}R_{tot} = \frac{1}{\frac{1}{R_1} + \frac{1}{R_1} + \frac{1}{R_3} + ...}{{< /katex >}}

#### Bråkform med 2 resistorer
{{< katex >}}R_{tot} = \frac{R_1*R_2}{R_1+R_2}{{< /katex >}}  
*Denna fungerar bara på två parallellkopplade motstånd.*

## Exempel

Om du lägger till en resistor i en parallellkrets så minskar resistansen eftersom strömmen får fler vägar att gå.

Om du tar bort en resistor i en parallellkrets så ökar resistansen eftersom strömmen får färre väggar att gå.

Om du lägger till eller tar bort en resistor i en paralellkrets så påverkas inte spänningen i kretsan.

Om du lägger till en resistor i en parallellkrets så ökar strömmen eftersom det finns fler vägar för den att gå genom kretsen.

Om du tar bort en resistor i en parallellkrets så minskar strömmen eftersom det finns färre vägar för strömmen att röra sig genomn kretsen.

### Beräkmningsexempel för resistans
| Data                                     |
| ---------------------------------------- |
| {{< katex >}} U = 30 V {{< /katex >}}    | 
| {{< katex >}} I_1 = 2 A {{< /katex >}}   |
| {{< katex >}} I_2 = 3 A {{< /katex >}}   |

![ Krets enlig datatabell ](/parallell1.png)

| Steg      | Uträkning av totala strömmen |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} I = I_1+I_2 {{< /katex >}}   |
| Uträkning | {{< katex >}} I = 2 A + 3 A  {{< /katex >}} |
| Resultat  | {{< katex >}} I = 5 A {{< /katex >}} |

| Steg      | Uträkning av totala resistansen allternativ 1 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} R_{tot} = \frac{U}{I} {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = \frac{ 30 V }{ 5 A } {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 6 \Omega {{< /katex >}} |

| Steg      | Uträkning av resistans 1 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} R_1 = \frac{U}{I_1} {{< /katex >}}   |
| Uträkning | {{< katex >}} R_1 = \frac{ 30 V }{ 2 A } {{< /katex >}} |
| Resultat  | {{< katex >}} R_1 = 15 \Omega {{< /katex >}} |

| Steg      | Uträkning av resistans 2 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} R_{tot} = \frac{U}{I_2} {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = \frac{ 30 V }{ 3 A } {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 10 \Omega {{< /katex >}} |

| Steg      | Uträkning av totala resistansen allternativ 2 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} \frac{1}{R_{tot}} = \frac{1}{R_1} + \frac{1}{R_2} {{< /katex >}}   |
| Uträkning | {{< katex >}} \frac{1}{R_{tot}} = \frac{1}{ 15 \Omega } + \frac{1}{ 10 \Omega } {{< /katex >}} |
| Uträkning | {{< katex >}} R_{tot} = \frac{1}{ 0.833333}  {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 6 \Omega {{< /katex >}} |


### Beräkmningsexempel för spänmning och ström:
| Data                                           |
| ---------------------------------------------- |
| {{< katex >}} I_1 = 5.25 A {{< /katex >}}         |
| {{< katex >}} I_2 = 3 A {{< /katex >}}         | 
| {{< katex >}} R_1 = 40 \Omega {{< /katex >}}   |
| {{< katex >}} R_1 = 70 \Omega {{< /katex >}}   |

![ Krets enlig datatabell ](/parallell2.png)

| Steg      | Uträkning av totala strömmen |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} I = I_1+I_2 {{< /katex >}}   |
| Uträkning | {{< katex >}} I = 5.25 A + 3 A  {{< /katex >}} |
| Resultat  | {{< katex >}} I = 8.25 A {{< /katex >}} |

| Steg      | Uträkning av spänning alternativ 1 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} U = I_1 * R_1 {{< /katex >}}   |
| Uträkning | {{< katex >}} U = 5 A * 45 \Omega {{< /katex >}} |
| Resultat  | {{< katex >}} U = 225 V {{< /katex >}} |

| Steg      | Uträkning av spänning alternativ 2 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} U = I_1 * R_1 {{< /katex >}}   |
| Uträkning | {{< katex >}} U = 3 A * 70 \Omega {{< /katex >}} |
| Resultat  | {{< katex >}} U = 225 V {{< /katex >}} |

| Steg      | Uträkning av totala resistansen allternativ 1 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} R_{tot} = \frac{U}{I} {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = \frac{ 30 V }{ 5 A } {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 6 \Omega {{< /katex >}} |

| Steg      | Uträkning av totala resistansen allternativ 2 |
| --------- | ---------------------------- |
| Formel    | {{< katex >}} \frac{1}{R_{tot}} = \frac{1}{R_1} + \frac{1}{R_2} {{< /katex >}}   |
| Uträkning | {{< katex >}} \frac{1}{R_{tot}} = \frac{1}{ 15 \Omega } + \frac{1}{ 10 \Omega } {{< /katex >}} |
| Uträkning | {{< katex >}} R_{tot} = \frac{1}{ 0.833333}  {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 6 \Omega {{< /katex >}} |

## Frågor

Vad händer om du lägger till till en resistor i en parallellkrets?

Vad händer om du tar bort en resistor i en parallellkrets?

Vad händer med spänningen över resistorerna i en parallellkrets om du lägger till en resistor?

Vad händer med spänningen över resistorerna i en parallellkrets om du tar bort en resistor?

Vad händer med strömmen i en parallellkrets om du lägger till en resistor?

Vad händer med strömmen i en parallellkrets om du tar bort en resisor?
