---
title: "4. Seriekrets"
---
# Seriekretsar
I seriekretsar kopplar man de komponenter i serie eller efter varandra, ungefär som ett
tåg. Detta kallas också för seriekopplingar. Det som händer seriekopplingen är att strömmen får svårare att ta sig fram, efter som det är fler motstånd at ta sig förbi, och då minskar strömmen.
Spänningen kommer däremot dela upp sig på varje del i seriekopplingen. Hur stor spänningen över komponent blir beror på hur stor resistorn är och hur stor strömmen är, för att räkna ut det avänder man Ohms-Lag.

## Order serie
Ordet serie i detta fall är samma princip som när man använder order i vanliga fall också så som:
 * Seriemördare
 * Serietidning
 * Seriespel
Serie betyder alltså att något sker i en följd efter varandra. En seriemördare mördar en sedan nästa osv,
till skillnad från tillexempel en massmördare som mördar många samtidigt.

## Uträkningar i seriekretsen
### Spänningen
Spänningn som kommer från spänningskällan kommmer att delas upp över de olika belastningar. Alla spänningarna övre belastningarna kommer tillsammans bli den spänning som spänningskällan ger.  
{{< katex >}}U = U_1+U_2+U_3...{{< /katex >}} 

### Strömmen
I en seriekrets finns det bara en väg för strömmen att gå. Därför finns det bara en ström i kretsen. Strömman är alltså lika stor över allt i kretsen.  
{{< katex >}}I = I_1 = 1_2 = I_3...{{< /katex >}}

### Resistansen
Eftersom strömmen måste gå igenom alla belastningar den ena efter den andra blir detn totala resistansen  summan av alla belastningarnas resistans.  
{{< katex >}}R_{tot} = R_1+R_2+R_3...{{< /katex >}}

## Exempel

Om du lägger till en belastning i serie så kommer den totala resistansen att öka eftersom strömmen får ytterligare ett hinder att passera.

Om du tar bort en belastning som sitter i serie och kopplar ihop så att strömmen kan passera direkt minskar resistansen eftersom strömmen slipper går igenom den belastningen.

Om du har två resistorer i serie och en har stor resistans och en har liten så kommer den med stor resistans få en hög spänning och den med låg resistanss kommer att få en låg spänning. Detta beror på att båda kommer att få samma ström och strömmen gånger resistansen ger spänningen enligt Ohms-lag. Detta gör att spänningen blir hög med hög resistans och låg med låg resistans.

### Beräkningsexempel för spänning:

| Data       |
| ---------- |
| {{< katex >}} I = 2 A {{< /katex >}}     | 
| {{< katex >}} R_1 = 150 \Omega {{< /katex >}}   |
| {{< katex >}} R_2 = 250 \Omega {{< /katex >}}   | 
| {{< katex >}} R_3 = 100 \Omega {{< /katex >}}   |

![ Krets enlig datatabell ](/serie1.png)

| Steg      | Uträkning av totala resistansen |
| --------- | ------------ |
| Formel    | {{< katex >}} R_{tot} = R_1+R_2+R_3 {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = 150 \Omega + 250 \Omega + 100 \Omega {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 500 \Omega {{< /katex >}} |

| Steg      | Uträkning av delsspänningen 1 |
| --------- | ------------ |
| Formel    | {{< katex >}} U_1 = R_1 * I {{< /katex >}}   |
| Uträkning | {{< katex >}} U_1 = 150 \Omega * 2 A{{< /katex >}} |
| Resultat  | {{< katex >}} U_1 = 300 V {{< /katex >}} |

| Steg      | Uträkning av delsspänningen 2 |
| --------- | ------------ |
| Formel    | {{< katex >}} U_2 = R_2 * I {{< /katex >}}   |
| Uträkning | {{< katex >}} U_2 = 250 \Omega * 2 A{{< /katex >}} |
| Resultat  | {{< katex >}} U_2 = 500 V {{< /katex >}} |

| Steg      | Uträkning av delsspänningen 3 |
| --------- | ------------ |
| Formel    | {{< katex >}} U_3 = R_3 * I {{< /katex >}}   |
| Uträkning | {{< katex >}} U_3 = 100 \Omega * 2 A{{< /katex >}} |
| Resultat  | {{< katex >}} U_3 = 200 V {{< /katex >}} |

| Steg      | Uträkning av totala spänningen, alternativ 1 |
| --------- | ------------ |
| Formel    | {{< katex >}} U = R_{tot} * I {{< /katex >}}   |
| Uträkning | {{< katex >}} U = 500 \Omega * 2 A{{< /katex >}} |
| Resultat  | {{< katex >}} U = 1000 V {{< /katex >}} |

| Steg      | Uträkning av totala spänningen, alternativ 2 |
| --------- | ------------ |
| Formel    | {{< katex >}} U = U_1+U_2+U_3{{< /katex >}}    |
| Uträkning | {{< katex >}} U = 300 V + 500 V + 200 V {{< /katex >}} |
| Resultat  | {{< katex >}} U = 1000 V {{< /katex >}} |

| Svar       |
| ---------- |
| {{< katex >}} I = 2 A {{< /katex >}}     | 
| {{< katex >}} R_1 = 150 \Omega {{< /katex >}}   |
| {{< katex >}} R_2 = 250 \Omega {{< /katex >}}   | 
| {{< katex >}} R_3 = 100 \Omega {{< /katex >}}   | 
| {{< katex >}} R_{tot} = 500 \Omega {{< /katex >}} |
| {{< katex >}} U_1 = 300 V {{< /katex >}} |
| {{< katex >}} U_2 = 500 V {{< /katex >}} |
| {{< katex >}} U_3 = 200 V {{< /katex >}} |
| {{< katex >}} U = 1000 V {{< /katex >}} |

### Beräkningsexempel för resistans och ström:

| Data       |
| ---------- |
| {{< katex >}} U = 30 V {{< /katex >}}     | 
| {{< katex >}} R_1 = 50 \Omega {{< /katex >}}   |
| {{< katex >}} U_2 = 10 V {{< /katex >}}   | 
| {{< katex >}} U_3 = 12 V {{< /katex >}}   | 

![ Krets enlig datatabell ](/serie2.png)

| Steg      | Uträkning av delspänning 1 |
| --------- | ------------ |
| Formel    | {{< katex >}} U_1 = U - (U_2 + U_3) {{< /katex >}}   |
| Uträkning | {{< katex >}} U_1 = 30V - (10V + 12V) {{< /katex >}} |
| Resultat  | {{< katex >}} U_1 = 8V {{< /katex >}} |

| Steg      | Uträkning av strömmen |
| --------- | ------------ |
| Formel    | {{< katex >}} I = \frac{U_1}{R_1}{{< /katex >}}   |
| Uträkning | {{< katex >}} I = \frac{8V}{50 \Omega}{{< /katex >}} |
| Resultat  | {{< katex >}} I = 0.16A {{< /katex >}} |

| Steg      | Uträkning av resitansen 2 |
| --------- | ------------ |
| Formel    | {{< katex >}} R_2 = \frac{U_2}{I}{{< /katex >}}   |
| Uträkning | {{< katex >}} R_2 = \frac{10V}{0.16A}{{< /katex >}} |
| Resultat  | {{< katex >}} R_2 = 62.5 \Omega {{< /katex >}} |

| Steg      | Uträkning av resitansen 3 |
| --------- | ------------ |
| Formel    | {{< katex >}} R_3 = \frac{U_3}{I}{{< /katex >}}   |
| Uträkning | {{< katex >}} R_3 = \frac{12V}{0.16A}{{< /katex >}} |
| Resultat  | {{< katex >}} R_3 = 75 \Omega {{< /katex >}} |

| Steg      | Uträkning av totala resistansen, alternativ 1 |
| --------- | ------------ |
| Formel    | {{< katex >}} R_{tot} = \frac{U}{I} {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = \frac{30V}{0.16A}{{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 187,5 \Omega{{< /katex >}} |

| Steg      | Uträkning av totala resistansen, alternativ 2 |
| --------- | ------------ |
| Formel    | {{< katex >}} R_{tot} = R_1 + R_2 + R_3 {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = 50 \Omega + 62.4 \Omega + 75 \Omega {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 187,5 \Omega{{< /katex >}} |

| Svar       |
| ---------- |
| {{< katex >}} U = 30 V {{< /katex >}}     | 
| {{< katex >}} R_1 = 50 \Omega {{< /katex >}}   |
| {{< katex >}} U_2 = 10 V {{< /katex >}}   | 
| {{< katex >}} U_3 = 12 V {{< /katex >}}   | 
| {{< katex >}} U_1 = 8V {{< /katex >}} |
| {{< katex >}} I = 0.16A {{< /katex >}} |
| {{< katex >}} R_2 = 62.5 \Omega {{< /katex >}} |
| {{< katex >}} R_3 = 75 \Omega {{< /katex >}} |
| {{< katex >}} R_{tot} = 187,5 \Omega{{< /katex >}}  |