---
Title: 11. Transformator
weight: 11
---
# Transformator

![Transformator](/trafo.png)

I en trnsformator går strömmen genom en spole och sedan tillbaka till spänningskällan. Spolen skapar ett magnetfällt som överförs med en järnbit till en annan spole.
Då kommer magnetfältet som rör sig genom jänrnbiten att skapa en spänning i den andra spolen. Genom att ha olika antal varv i spolarna så kan spänningen ändra upp eller ner.

Det är bara när magnetfältet rör sig fram och tillbaka som det blir en spänning på den andra spolen. Därför måste man använda växelspänning för att den ska fungera för att få magnetfälltet att röra sig fram och tillbaka. Om en transformator ansluts till likspänning så kommer det ingen spänning från den andra spolen.

## Magnetfällt
Magnetfällt är det som finns runt en magnet som går från N till S på magneten. När en ledare korsar ett mangetfällt eller ett magnetfällt korsar en ledare så kommer det att skapas en spänning i ledare. Det är också så att om det går en ström i en ledare så skapas det ett magnetfällt runt den. Det är hur både el-motorer/generatorer och transformatorer fungerar, alltså med hjälp av mangetfällt som rör sig och/eller ledare med ström i.

## Primär och sekundärsida
![Transformator Primärsida och Sekundärsida](/trafops.png)

Den sida på transformatorn som får spännigen från  till exempel eluttaget eller en generator kallas för primärsida.
Den sida på transformatorn som är kopplad till belastningen till exempel en lampa kallas för sekundärsida.
Primärsida kan också kallas för primärspole, primärlindning.
Sekundärsida kan också kallas för sekundärspole, sekundärlinding.

Det är föhållander mellan antalet varv på primärsidan och sekundärsidan som bestämmer om spänningen ska öka eller minska. Den sidan med flest varv har den högsta spänningen.

En transformator har alltid samma effekt på båda sidorna. I praktiken så är effekten lite högre på primärsidan eftersom det finns lite förluster på olika ställen. Effekten är alltid minst lika stor på primärsidan som sekundärsidan.

När du köper en transformator så kan den vara märkt med tillexempel 40/5V det betyder att den ska ha 40V på primärsidan och ger 5V på sekundärsidan.

## Exempel

En transoformator med märkningen 50/45V ska ha spänningen 50V på primärsidan och får då 45V på sekundärsidan.

En transformator som belastas med en effekt på sekundärsidan kommer att belasta primärsidan med lika mycket plus eventuella förluster på vägen.

En transformator med många varm på primärsidan och få på sekundärsidan sänker spänningen.

En transformator med få varv på primärsidan och många på sekundärsidan höjer spänningen.

En transformator med lika många varm på sekundärsidan och primärsidan ändrar inte på spänningen.

## Formel
{{< katex >}} \frac{n_1}{n_2} = \frac{U_1}{U_2} {{< /katex >}} 

### Beräkningar

#### Primär många varv sekundär få varv

| Data       |
| ---------- |
| {{< katex >}} n_1 = 2000 {{< /katex >}}     | 
| {{< katex >}} n_2 = 1000 {{< /katex >}}     | 
| {{< katex >}} U_1 = 230V {{< /katex >}}     | 

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} \frac{n_1}{n_2} = \frac{U_1}{U_2} {{< /katex >}}  |
| Uträkning steg 1 | {{< katex >}} \frac{2000}{1000} = \frac{230V}{U_2} {{< /katex >}}  |
| Uträkning steg 2 | {{< katex >}} 2 = \frac{230V}{U_2} {{< /katex >}}  |
| Uträkning steg 3 | {{< katex >}} U_2 = \frac{230V}{2} {{< /katex >}}  |
| Resultat  | {{< katex >}} U_2 = 115V {{< /katex >}}   |

| Svar      |
| ---------- |
| {{< katex >}} n_1 = 2000 Varv  {{< /katex >}}     | 
| {{< katex >}} n_2 = 1000 Varv  {{< /katex >}}     | 
| {{< katex >}} U_1 = 230V {{< /katex >}}     | 
| {{< katex >}} U_2 = 115V {{< /katex >}}     | 

#### Primär få varv sekundär många varv

| Data       |
| ---------- |
| {{< katex >}} n_1 = 1500 {{< /katex >}}     | 
| {{< katex >}} n_2 = 3000 {{< /katex >}}     | 
| {{< katex >}} U_2 = 30V {{< /katex >}}     | 

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} \frac{n_1}{n_2} = \frac{U_1}{U_2} {{< /katex >}}  |
| Uträkning steg 1 | {{< katex >}} \frac{1500}{3000} = \frac{U_1}{30V} {{< /katex >}}  |
| Uträkning steg 2 | {{< katex >}} 0.5 = \frac{U_1}{30V} {{< /katex >}}  |
| Uträkning steg 3 | {{< katex >}} U_1 = 30V * 0.5 {{< /katex >}}  |
| Resultat  | {{< katex >}} U_1 = 15V {{< /katex >}}   |

| Svar      |
| ---------- |
| {{< katex >}} n_1 = 2000 Varv  {{< /katex >}}     | 
| {{< katex >}} n_2 = 1000 Varv  {{< /katex >}}     |
| {{< katex >}} U_2 = 30V {{< /katex >}}     |
| {{< katex >}} U_1 = 15V {{< /katex >}}     | 

#### Ström före och efter

| Data       |
| ---------- |
| {{< katex >}} U_1 = 230V {{< /katex >}}     | 
| {{< katex >}} U_2 = 48V  {{< /katex >}}     | 
| {{< katex >}} I_2 = 2.3 A {{< /katex >}}     | 

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} P = U_2 * I_2  {{< /katex >}}  |
| Uträkning | {{< katex >}} P = 48V * 2.3A {{< /katex >}}  |
| Resultat  | {{< katex >}} P = 110.4 W {{< /katex >}}  |

| Steg      | Exempel      |
| --------- | ------------ |
| Formel    | {{< katex >}} I_1 = \frac{P}{U} {{< /katex >}}  |
| Uträkning | {{< katex >}} I_1 = \frac{110.4W}{230V}{{< /katex >}}  |
| Resultat  | {{< katex >}} I_1 = 0.48A {{< /katex >}}  |

| Svar      |
| ---------- |
| {{< katex >}} U_1 = 230V {{< /katex >}}     |
| {{< katex >}} U_2 = 48V  {{< /katex >}}     |
| {{< katex >}} I_2 = 2.3A {{< /katex >}}    |
| {{< katex >}} P = 110.4W {{< /katex >}}    |
| {{< katex >}} I_1 = 0.48A {{< /katex >}}         |

## Frågor

Vilken spänning har en transoformator med märkningen 50/45V på primärsidan?

Vilken spänning har en transoformator med märkningen 50/45V på sekundärsidan?

Hur stor blir effekten på primärsidan på en transformator som belastas med en effekt på sekundärsidan?

Vad händer med spänningen på sekundärsidan i en transformator med många varm på primärsidan och få på sekundärsidan?

Vad händer med spänningen på sekundärsidan i en transformator med få varv på primärsidan och många på sekundärsidan?

Vad händer med spänningen på sekundärsidan i en transformator med lika många varm på sekundärsidan och primärsidan?
