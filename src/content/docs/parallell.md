---
title: "5. Parallell krets"
---
# Parallellkoppling

I parallellkopplingar kopplas de komponenter som ska användas på varandra, eller parallellt.
Detta resulterar i att strömmen får fler vägar att ta sig fram. Eftersom det finns fler vägar för strömmen så går det mer ström ju fler komponenter som koppas in. Mer ström betyder ju att den totala resistansen måste ha blivit mindre.
Den totala resistansen blir alltså mindre än de olika delresistanserna i en parallellkoppling. En bra minnesregel är därför att totalresistansen alltid blir mindre än den minsta resistansen i en
parallellkoppling.

## Ordet parallell
För att komma ihåg ordet vad ordet parallell betyder så är det samma ord som du använder i andra lägen så som:
 * Parallella universum
 * Parallella linjer
 * Parallellslalom
Ordet paralell betyder alltså bara att något ligger vid sidan av varandra. Parallella saker korsar inte varandra, när du har dina skidor paralellt så går det bra men korsar du dem så ramlar du direkt.

### Spänningen
{{< katex >}}U = U_1 = U_2 = U_3...{{< /katex >}} 

### Strömmen
{{< katex >}}I = I_1 + 1_2 + I_3...{{< /katex >}}

### Resistansen basform
{{< katex >}}\frac{1}{R_{tot}} = \frac{1}{R_1} + \frac{1}{R_1} + \frac{1}{R_3} + ...{{< /katex >}}

### Resistansen Beräkningsform
{{< katex >}}R_{tot} = \frac{1}{\frac{1}{R_1} + \frac{1}{R_1} + \frac{1}{R_3} + ...}{{< /katex >}}

### Resistansen bråkform med 2 resistorer
Denna fungerar bara på två parallellkopplade motstånd.  
{{< katex >}}R_{tot} = \frac{R_1*R_2}{R_1+R_2}{{< /katex >}}

## Exempel
I exemplet så är två resistanser parallellkopplade. Det syns för att strömmen kommer till en
förgreningspunkt. Spänningen i uppgiften är 30 V.
Resistanserna i uppgifterna är R 1 är 100 Ω och R 2 är 200 Ω
Spänningen i uppgiften är 30 V. Den spänning som
ligger över resistorn R 1 är också 30 V och det är även
spänningen på R 2 . Spänningen delas alltså inte upp
utan spänningen är samma på alla delar i en
parallellkoppling.

Tittar man på strömmen genom R 1 så blir den enligt
Ohms lag 3 A.

På samma sätt kan man räkna ut strömmen genom R 2 .

Om det åker 0,3 A till R 1 och 0,15 A till R 2 så måste det
komma 0,45 A från ström och spänningskällan. Detta
samband kom Kirchhoff på och kallas Kirchhoffs
strömlag.

För att räkna ut den totala resistansen i kopplingen så används Ohms lag igen.

I exemplet är 10 Ω det minsta motståndet och 6,7 Ω är mindre.
Ett sätt att räkna ut totalresistansen i en parallellkoppling är att använda formlerna:

## Exempel lika stora
