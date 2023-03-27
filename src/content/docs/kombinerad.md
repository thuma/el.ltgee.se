---
title: "6. Kombinerad krets"
weight: 6
---
# Kombinerad krets

![Kombinerad krets](/kombinerad.png)

I en kombinerad krets så finns det både serie och parallellkopplade delar. Det finns inga formler som gäller för kombinerade kretsar. Du måste själv räkna ut de olika delarna var för sig så att du får rena serie eller parallellberäkningar att lösa.

För att lösa ut och ersätta seriekopplingar/parallellkopplingar i kombinerade kretsar behöver du hitta en ren seriekrest eller en ren parallellkrets inne i den kombinerade kretsen. När du hittat två eller fler resistorer som är kopplade i serie eller parallellt med varandra, kan du på vanligt sätt räkna ut vad resistansen är för dem tillsammans.

## Exempel

### Parallellkoppling i en seriekoppling
![Krets där en parallell koppling ersätts av en ersättnings resistans](/kombinerad1.png)
I kretsen ovan så behöver du räkna ut ersättningsresistansen för R2 och R3 tillsammans. För att sedan få en ren seriekrets att räkna på.

### Seriekoppling i en parallellkoppling
![Krets där en parallell koppling ersätts av en ersättnings resistans](/kombinerad2.png)
I kretsen ovan så behöver du räkna ut ersättningsresistansen för R1 och R2 tillsammans. För att sedan få en ren parallellkrets att räkna på.

### Ändring av parallellkrets i seriekrets
![Krets där en resistor läggs till](/kombineradex1.png)

Om du lägger till en resistor (R4) parallellt med R2 och R3 i kretsen ovan så kommer den totala resistansen att minska eftersom strömmen får fler vägar att gå.
Då kommer strömmen att öka i kretsen, strömmen genom R1 blir därför högre. En högre ström leder till ett större spänningsfall över R1. Detta gör att spänningen över R2 & R3 minskar. Detta gör att strömmen genom R2 och R3 minskar när resistorn kopplas in paralellt med R2 och R3.

### Ändring av krets ytterigare en parallell resistor.
![Krets där en resistor läggs till](/kombineradex2.png)
Om du lägger till en resistor (R4) paralellt med R1 i kretsen så kommer den toala resistansen att minska eftersom strömmen får fler vägar att gå. Det kommer att innebära en större ström genom R2 och R3 som ger ett större spänningsfall över R2 och R3 detta gör att R1 får en längre spänning och en mindre ström.

### Ändring av krets ytterigare en parallell resistor.
![Krets där en resistor läggs till](/kombineradex3.png)
Om du lägger till en resistor (R4) paralellt med R3 i kretsen så kommer den toala resistansen att minska eftersom strömmen får fler vägar att gå. Eftersom det är samma spänning över R1, R2 och R3 efter detta också så kommer spänningarna och strömmarna genom dem att vara samma som innan.

### Ändring av krets ytterligare en reistor i serie.
![Krets där en resistor läggs till](/kombineradex4.png)

Om du lägger till en resistor (R4) i serie med R3 i kretsen så kommer den toala resistansen att öka eftersom strömmen måste ta sig igenom fler motstånd. Eftersom det är samma spänning över R1, R2 så kommer inget att hända med spänningen över R1 och R2. Strömmen genom R1 och R2 kommer inte heller att förändras. Spänningn över R3 kommer att minska eftersom det också kommer att bli ett spänningsfall över R4.

## Frågor

Vad händer i kretsen om du lägger in en resistor parallellt med övriga belastningar?
Vad händer i kretsen om du lägger in en resistor i serie med övriga belastningar?
