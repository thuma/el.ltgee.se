---
title: "11. Fasförskjutning"
weight: 11
---

# Fasförskjutning
![Fasförskjutning](/fasf.png)

Fasförskjutning är när strömmen och spänningen inte går i takt. Som i bilen ovan så har ström och spänning sina topp och botten värden vid olika tidpunkter. När ström och spänningn inte går i takt så fungerar inte Effekt-formeln och Ohms lag som vanligt längre.

## Induktiv
När du kopplar in en spole i en krets så kommer strömmen att komma efter spänningen. Det beror på att magnetfältet som skapas i spolen bromsar strömmen. På bilden så kan du se hur strömmen (blå) kommer efter spänningen (röd).
![Spole med spänning](/spole24AC.svg)  
![Strömmen efter](/lfi.png)

## Kapasitiv
När du kopplar in en kondensatorn i en krets så kommer strömmen att komma före spänningen. Det beror på att strömmen tidigare har blivit lagrad i kondensatorn och skickas ut redan innan spänningen kommer. På bilden så kan du se hur strömmen (blå) kommer före spänningen (röd).
![Spole med spänning](/24vcond.svg)  
![Ström före](/cfi.png)

## Ordet fas

Ordet effekt används även utanför elvärlden då betyder det nästan samma sak. Ett exempel är att säga ett effekten av att slå sig på tummen med hammaren är att man får ont. Om du slår dig jättehårt med hammaren på tummern så får du jätteont villken är en stor effekt. Om du slår dig lite på tummen får du lite ont eller liten effekt.

## Ordet förskjutning

Försjutning betyder att något är flyttat, att något inte ligger tillsammans.

## Trianglar
När det finns fasförskjutning i en krets så kan du beskriva hur de olika delarna hänger samman med hjälp av trianglar. Grundtrianglarna i en enkel krets med fasförskjutning är dessa:
![Impedeans,Spänning,Effekt](/Fasförskjutning.svg)
{{< katex >}}\varphi{{< /katex >}} är samma i alla trianglarna. Vet du vnikeln {{< katex >}}\varphi{{< /katex >}} i en krets så vet du de andra också, eftersom det är samma.

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

| Steg      | Räkna ut fasförskjutning i grader |
| --------- | ------------ |
| Formel   | {{< katex >}} \varphi = Cos^{-1}(Cos\varphi) {{< /katex >}}     |
| Uträknning  | {{< katex >}} \varphi = Cos^{-1}(0.75) {{< /katex >}}     |
| Resultat  | {{< katex >}} \varphi  = 41.4\degree {{< /katex >}}     |

| Svar       |
| ---------- |
| R = 15Ω    |
| Z = 20Ω    |
| {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}  |
| {{< katex >}} \varphi  = 41.4\degree {{< /katex >}}     |

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

| Steg      | Räkna ut fasförskjutning i grader |
| --------- | ------------ |
| Formel   | {{< katex >}} \varphi = Cos^{-1}(Cos\varphi) {{< /katex >}}     |
| Uträknning  | {{< katex >}} \varphi = Cos^{-1}(0.75) {{< /katex >}}     |
| Resultat  | {{< katex >}} \varphi  = 41.4\degree {{< /katex >}}     |

| Svar        |
| ----------- |
| P = 150W    |
| S = 200VA   |
| {{< katex >}} Cos\varphi = 0.75 {{< /katex >}}  |
| {{< katex >}} \varphi  = 41.4\degree{{< /katex >}}  |

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

### Beräkningsexempel impedans och ström och spänning:

| Data       |
| ---------- |
| {{< katex >}} Z = 300 \Omega{{< /katex >}}    |
| {{< katex >}} I = 0.32 A {{< /katex >}}  |
| {{< katex >}} U_R = 72 V  {{< /katex >}}  |

| Steg      | Räkna ut Spänningen |
| --------- | ------------ |
| Formel    | {{< katex >}} U = I * Z {{< /katex >}}         |
| Uträkning | {{< katex >}} U = 0.31 A * 300 \Omega {{< /katex >}}     |
| Resultat  | {{< katex >}} U = 96V {{< /katex >}}     |

| Steg      | Räkna ut spänningen över reaktiva lasten |
| --------- | ------------ |
| Formel    | {{< katex >}} U_L^2 = U^2-U_R^2 {{< /katex >}}         |
| Uträkning | {{< katex >}} U_L = \sqrt{96V^2-72V^2} {{< /katex >}}     |
| Resultat  | {{< katex >}} U_L = 63.5V {{< /katex >}}     |

| Steg      | Räkna ut Skenbara effekten |
| --------- | ------------ |
| Formel    | {{< katex >}} S = U * I {{< /katex >}}         |
| Uträkning | {{< katex >}} S = 96V * 0.32A {{< /katex >}}     |
| Resultat  | {{< katex >}} S = 30.72 \text{VA} {{< /katex >}}     |

| Steg      | Räkna ut reaktiva effekten |
| --------- | ------------ |
| Formel    | {{< katex >}} Q_L = U_L * I {{< /katex >}}         |
| Uträkning | {{< katex >}} Q_L = 63.5V * 0.32A {{< /katex >}}     |
| Resultat  | {{< katex >}} Q_L = 20.32 \text{VAR} {{< /katex >}}     |

| Steg      | Räkna ut aktiva effekten |
| --------- | ------------ |
| Formel    | {{< katex >}} P = U_R * I {{< /katex >}}         |
| Uträkning | {{< katex >}} P = 72V * 0.32A {{< /katex >}}     |
| Resultat  | {{< katex >}} P = 23,04W {{< /katex >}}     |

| Svar        |
| ----------- |
| {{< katex >}} Z = 300 \Omega{{< /katex >}}    |
| {{< katex >}} I = 0.32A {{< /katex >}}  |
| {{< katex >}} U_R = 72 V  {{< /katex >}}  |
| {{< katex >}} U = 96VA {{< /katex >}}  |
| {{< katex >}} U_L = 63.5V {{< /katex >}}     |
| {{< katex >}} S = 30.72 \text{VA} {{< /katex >}}   |
| {{< katex >}} Q_L = 20.32 \text{VAR} {{< /katex >}}     |
| {{< katex >}} P = 23,04W {{< /katex >}}     |



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
| Spänning över induktiv reaktans | {{< katex >}}U_l{{< /katex >}}   | Volt        | V                |
| Spänning över kapasitiv reaktans | {{< katex >}}U_c{{< /katex >}}   | Volt        | V                |
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
