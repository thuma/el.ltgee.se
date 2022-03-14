---
title: "11. Fasförskjutning"
weight: 11
---

# Fasförskjutning

![Fasförskjutning](/fasf.png)

Spole kommer strömmen efter.
Induktiv  
![Spole med spänning](/spole24AC.svg)  
![Strömmen efter](/lfi.png)

Kondensator kommer strömmen före.
Capasitiv  
![Spole med spänning](/24vcond.svg)  
![Ström före](/cfi.png)

## Ordet fas

Ordet effekt används även utanför elvärlden då betyder det nästan samma sak. Ett exempel är att säga ett effekten av att slå sig på tummen med hammaren är att man får ont. Om du slår dig jättehårt med hammaren på tummern så får du jätteont villken är en stor effekt. Om du slår dig lite på tummen får du lite ont eller liten effekt.

## Ordet förskjutning

## Faförskjutniung och effekt

### Skenbar effekt
{{< katex >}}S = U * I{{< /katex >}}

### Effekt
{{< katex >}}P = U * I * Cos\varphi{{< /katex >}}

### Induktiv reaktiv effekt
{{< katex >}}Q_l = U * I * Sin\varphi{{< /katex >}}

### Kapasitiv reaktiv effekt
{{< katex >}}Q_c = U * I * Sin\varphi{{< /katex >}}

## Fasförskjutet motstånd
### Resistans
{{< katex >}}R = Z * Cos\varphi{{< /katex >}}

### Impedans
{{< katex >}}Z = R / Cos\varphi{{< /katex >}}

### Kapacitiv Reaktans
{{< katex >}}Q_c = Z * Sin\varphi{{< /katex >}}

### Induktiv Reaktans
{{< katex >}}Q_l = Z * Sin\varphi{{< /katex >}}

## Fasförskjutna spänningar

### Spänning över resistans
{{< katex >}}U_r = U * Cos\varphi{{< /katex >}}

### Huvudspänning
{{< katex >}}U = U_r / Cos\varphi{{< /katex >}}

### Spänning över induktans
{{< katex >}}U_l= U * Cos\varphi{{< /katex >}}

### Spänning över kapasitans
{{< katex >}}U_c= U * Cos\varphi{{< /katex >}}

## Exempel

Om en spole är inkopplad i kretsen så kommer strömmen att komma efter spänningen.

Om en kondensator är inkopplad i kretsen så kommer strömmen att komma före spänningen.

Om både en kondensator och en spole är inkopplad i en krets så kommer de att motverka varandra så fasförskjutningen kommer att minska.

Om det är rätt storlek på kondesator och spole så kommer fasförskjutningen att försvinna helt.

### Beräkningsexempel fasförskjutning resistans och impedans:

| Data       |
| ---------- |
| R = 15Ω    |
| Z = 20Ω    |

| Steg      | Räkna ut fasförskjutning |
| --------- | ------------ |
| Formel    | {{< katex >}} Cos\varphi = \frac{R}{Z} {{< /katex >}}         |
| Uträkning | {{< katex >}} Cos\varphi = \frac{15Ω}{20Ω} {{< /katex >}}     |
| Resultat faktor | {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}     |
| Resultat i grader  | {{< katex >}} Cos^{-1}\varphi(0.75) = 41.4\degree {{< /katex >}}     |

| Svar       |
| ---------- |
| R = 15Ω    |
| Z = 20Ω    |
| {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}  |

### Beräkningsexempel fasförskjutning skenbar effekt och effekt:

| Data       |
| ---------- |
| P = 150W    |
| S = 200VA    |

| Steg      | Räkna ut fasförskjutning |
| --------- | ------------ |
| Formel    | {{< katex >}} Cos\varphi = \frac{P}{S} {{< /katex >}}         |
| Uträkning | {{< katex >}} Cos\varphi = \frac{150W}{200VA} {{< /katex >}}     |
| Resultat faktor | {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}     |
| Resultat i grader  | {{< katex >}} Cos^{-1}\varphi(0.75) = 41.4\degree {{< /katex >}}     |

| Svar        |
| ----------- |
| P = 150W    |
| S = 200VA   |
| {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}  |

### Beräkningsexempel effekt och skenbar effekt med fasförsjutning:

| Data       |
| ---------- |
| P = 300W    |
| {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}  |

| Steg      | Räkna ut fasförskjutning |
| --------- | ------------ |
| Formel    | {{< katex >}} S = \frac{P}{Cos\varphi} {{< /katex >}}         |
| Uträkning | {{< katex >}} S = \frac{300W}{0.75} {{< /katex >}}     |
| Resultat  | {{< katex >}} S = 400VA {{< /katex >}}     |

| Svar        |
| ----------- |
| P = 150W    |
| {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}  |
| S = 400VA   |


## Frågor

Vad händer med strömmen om en spole är inkopplad i en krets?

Vad händer med strömmen om en kondensator är inkopplad i en krets?

Vad händer om du kopplar in både kondensator och en spole i en krets?

Vad händer om du kopplar in en kondensator och en spole med lika stor reaktans?

## Storheter och enheter
| Storhet      | Beteckning | Enhet       | Beteckning |
| ------------ | ------------------ | ----------- | ---------------- |
| Ström (Toppvärde)       | {{< katex >}}î   {{< /katex >}}            | Ampere      | A                |
| Ström (Effektivvärde) | {{< katex >}}I    {{< /katex >}}              | Ampere      | A                |
| Spänning (Toppvärde) | {{< katex >}}û{{< /katex >}} | Volt     | V                | 
| Spänning (Effektivvärde)     | {{< katex >}}U{{< /katex >}}                  | Volt        | V                |
| Spänning över reaktans | {{< katex >}}U_l{{< /katex >}}   | Volt        | V                |
| Spänning över kapacitans | {{< katex >}}U_c{{< /katex >}}   | Volt        | V                |
| Resistans     | {{< katex >}}R {{< /katex >}}                 | Ohm         | Ω                |
| Kapacitiv reaktans |  {{< katex >}}X_c{{< /katex >}}     |  Ohm         | Ω                |
| Induktiv reaktans  |  {{< katex >}}X_l{{< /katex >}}     | Ohm         | Ω                |
| Impedans | {{< katex >}}Z{{< /katex >}} | Ohm         | Ω                |
| Effekt       | {{< katex >}}P{{< /katex >}}                  | Watt        | W               |
| Skenbar effekt      | {{< katex >}}S{{< /katex >}}                  | VoltAmpere        | VA                |
| Reaktiv effekt induktiv     | {{< katex >}} Q_l {{< /katex >}}                  | VoltAmpereReaktiv       | VAR            |
| Reaktiv effekt kapasitiv      | {{< katex >}} Q_c {{< /katex >}}                  | VoltAmpereReaktiv       | VAR       |
| Fasförskjutning | {{< katex >}} \varphi {{< /katex >}} | Grader |  {{< katex >}} \degree {{< /katex >}} |
| Effektfaktor | {{< katex >}} Cos\varphi {{< /katex >}} | Faktor |  ingen |
| Verkninsgrad | {{< katex >}} \eta {{< /katex >}}                 | Procent / Faktor     | % / ingen                | 
| Periodtid | {{< katex >}} t {{< /katex >}}  | Sekunder     | s                | 
| Frekvens | {{< katex >}} f {{< /katex >}}                  | Hertz     | Hz                | 
| Resistivitet | {{< katex >}}\rho{{< /katex >}} | Ohm per meter per kvadratmillimeter | Ohm/m/mm² | 
| Längd        | {{< katex >}}l {{< /katex >}}                 | Meter       | m                |
| Tvärsnittsarea | {{< katex >}}A {{< /katex >}}               | Kvadratmillimeter | mm²| 
