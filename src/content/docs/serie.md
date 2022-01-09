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
I exemplet bredvid är två motstånd seriekopplade och anslutna till en
spänningskälla på 30 V.

Låt oss säga att R 1 är 100 Ω och R 2 är
200 Ω så kommer det totala motståndet i
kopplingen bli 300 Ω. Formeln ser ut så
här:

Spänningen i uppgiften är 30 V och då
blir strömmen i kopplingen enligt Ohm´s
lag 0,1 A.

Strömmen är lika stor i hela kopplingen,
är det 0,1 ampere som kommer ut ur spänningskällan är det 0,1 ampere i R 1 och även 0,1
ampere som åker tillbaka. Tänk vattenslangar och vatten, det vatten som åker in i slangen
måste ut till slut.

Spänningen på resistor 1 blir då enligt ohms lag 10 V.
Spänningen som finns på R 2 kan räknas ut med Ohms lag men man kan också använda
Kirchhoffs spänningslag. Kirchhoff sa att delspänningarna är lika med totalspänningen eller:

I uppgiften måste alltså U 2 bli 20 V eftersom


Krets med beräkningsexemppel U

| Data       |
| ---------- |
| {{< katex >}} I = 2 A {{< /katex >}}     | 
| {{< katex >}} R_1 = 150 \Omega {{< /katex >}}   |
| {{< katex >}} R_2 = 250 \Omega {{< /katex >}}   | 
| {{< katex >}} R_3 = 100 \Omega {{< /katex >}}   | 

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

| Data       |
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

Krets med beräkningsecempel R

| Data       |
| ---------- |
| {{< katex >}} U = 30 V {{< /katex >}}     | 
| {{< katex >}} R_1 = 50 \Omega {{< /katex >}}   |
| {{< katex >}} U_2 = 10 V {{< /katex >}}   | 
| {{< katex >}} U_3 = 12 V {{< /katex >}}   | 

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
| Formel    | {{< katex >}} R_{tot} = \frac{U}/{I} {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = \frac{30V}/{0.16A}{{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 187,5 \Omega{{< /katex >}} |

| Steg      | Uträkning av totala resistansen, alternativ 2 |
| --------- | ------------ |
| Formel    | {{< katex >}} R_{tot} = R_1 + R_2 + R_3 {{< /katex >}}   |
| Uträkning | {{< katex >}} R_{tot} = 50 \Omega + 62.4 \Omega + 75 \Omega {{< /katex >}} |
| Resultat  | {{< katex >}} R_{tot} = 187,5 \Omega{{< /katex >}} |

| Data       |
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