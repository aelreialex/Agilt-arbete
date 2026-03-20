# Individuella reflektioner

Svara på var och en av frågorna nedan individuellt (minst 100 tecken per fråga)

## Frågor

### Inledning

#### Vad var ditt mål med projektet initialt?

Lära mig hur man jobbar i scrum samt hur projects och tasks fungerar och få en större inblick i olika problem som kan uppstå under ett projekts gång.

#### Hur kände du inför att arbeta i ett riktigt projekt med ett riktigt team?

Inte speciellt mycket vi har arbetat i grupp under varje kurs under denna utbildningen så man har blivit väldigt van vid det. Så det kändes lugnt.

### Planering och genomförande

#### Hur tycker du att planeringen inför projektet fungerade?

Mycket bra vi gick igenom vad vi skulle göra i projects via userstorys för att sedan börja skissa upp en figmaskiss över hur vi tänkte att applikationen skulle se ut.

#### Vad har du bidragit med i planeringen, samt utvecklandet av applikationen.

Bidrog mer med user storysen och projects sidan än figma skissen. Under applikationens gång har jag gjort för det mesta javascript men också lite css men inte mycket. bidrog med menu sidan exempelvis.

#### Beskriv med dina egna ord, er applikation

En applikation för att kunna beställa mat över nätet istället för att behöva stå i kö på plats. nu gjorde vi bara hembeställningsfunktionen men skulle anta att man ska kunna beställa till plats med en timer för när det är klart och ha en orderhistorik.

### Teamets utmaningar och lösningar

#### Vika var de största utmaningarna för dig?

Största utmaningen för mig var menu sidan eftersom via vår skiss skulle vi ha en onklick på menyn då ska det poppa upp hur många du vill lägga till i beställningen. tbh svårare än vad man kan tro. men lärde mig väldigt mycket på det också.

#### Hur löste eller hanterade du dessa utmaningar?

Frågade efter hjälp eller ja försökte se om någon hade några ideer för hur man kunde lösa det. Men tror vi alla hade svårt för det kollade runt på youtube och frågade ai om vägledning till slut förstod jag ett sätt man kunde lösa det på.

#### Vilka kompromisser inom teamet har du fått göra under projektets gång?

Inte många tror vi har haft ett väldigt bra flöde under projektetsgång väldigt bra grupp synergi där man lyssnar på varandra och tar ett gemensamt grupp beslut.

### Individuell reflektion och utvärdering

#### Vad lärde du dig under projektets gång?

Väldigt mycket ifall jag ska vara ärlig har setat en del med javascript kanske lite för mycket. Men det har lärt mig att se fel också på sidor bara av att kolla på printscreens kan jag se eller få ett hum om vad som kan spöka. Så har lärt mig väldigt mycket där. Också lärt mig om projects/tasks/label vi använde inte det i vårat men vi lekte med det och kollade hur man gjorde.

#### Finns det någonting du skulle velat göra annorlunda om du fick chansen igen?

Mer tasks för att få en större helhet på uppgifterna vissa var absolut mycket svårare än de andra. Detta skulle släppa på press man kan ha över att det tar lång tid. Och använda labels för att sätta ihop saker som hör tillsammans. Sen nu i efterhand vet man ju vilka delar man behöver tidigt in i projektet för att buggtesta hade lagt upp dem tidigare i userstoryn.

#### Vilka möjligheter ser du med de kunskaper du fått under arbetet med projektet?

Vet inte känner fortfarande att jag måste utvecklas enormt mer i javascript fronten för att få det lätt ut på marknaden efter utbildningen. Men märker att saker som var svårare lossnar lite.

### VG-frågor (minst 200 tecken)

#### Beskriv minst tre fördelar med att arbeta agilt och motivera varför de är viktiga. Använd exempel från ert projekt för att styrka dina argument.

Första man får en bra diskution där alla kommer med sina åsikter över vad som är bra vad som är dåligt vilket gör att man får en större överblick av projektet och hur det ska se ut. exempelvis är jag inte direkt en designer men i vår grupp hade vi några som var perfekta för det vilket skapar en snygg design.

Det är också ganska skönt att kunna dela upp arbetet mellan varandra så att det går snabbare. Sen att ha 15 mins daily möten (kan ha gått över till kodhjälpning) var bra för att se hur alla ligger till om någon hade fastnat eller om nån visste att nu kommer jag behöva hjälp. Så att ingen fastnar helt i onödan när det finns hjälp att få.

Känslan att ha någon o bolla ideer med om det behövs är också otroligt viktigt känner jag i kodning då man kan fastna i sitt egna tänk lite för mycket.


#### Beskriv en konkret lösning du föreslagit. Varför ansåg du att den var bäst? Jämför med minst en annan möjlig lösning och förklara varför ni inte valde den.

Kan inte riktigt komma på någon speciell men på menu sidan la jag till pointer-events: none för att min js skulle fungera och inte få errors när man klickade på de 2 p taggarna / span som ligger över elementet man ska klicka på. ansåg att den var bäst för kom inte på något annat. Vi diskutera inte riktigt sånna hära lösningar under projektet utan vi gjorde våra egna userstorys o behövde vi hjälp satt vi med dem sen gick vi alltid igenom vad vi hade gjort via skärmdelning och förklara varför.

Jag la också till i orderInformations som en array i local som spar ner alla ordrar datum och ordernummer. Kom på i huvudet hur jag kunde löst allt med användare så att dem fick sina egna orderlistor men hade inte tid att implementera det innan vi skulle vara färdiga.

Men javascript har vi inte riktigt sagt att det finns bättre lösningar vi har gått på dem var o en har gjort sen försökt hjälpa varandra istället så lösningen ska fungera.

#### Ge minst två exempel på lösningar ni valde bort. Analysera varför ni avstod från dem. Hur påverkade det projektet? Kunde något ha gjorts annorlunda?

Svår fråga vi valde bort att inte ha orderhistoriken för users för vi hann inte med det riktigt att lägga in för individuella användare beroende på vem som loggat in. Vi kunde ha kollat på det tidigare men tror man blir ganska blind för sånna detaljer när man börjar projektet man tänker inte att det ska vara anpassat till en användare man kör på sin egna user story som skapar nog med problem för en. Vi hann helt enkelt inte med men vi visste hur vi skulle göra för att fixa detta.

Vi prioriterade bort responsiviteten också då vi kände att det skulle behöva delas upp så mycket och ta aldeles för mycket tid så här prioriterade vi att bara få ut en fullständigt flöde från login till orderkvitto. Vi borde lagt in responsiteten direkt för varje sida innan man skickade in dem som klar och inte ha dem som en user story.

#### Reflektera kring hur den kod du bidragit med skulle kunna förbättras, ge konkreta exempel.

Mycket så jäkla mycket. Skulle jag kunna förbättra min kod hade jag gjort om eller försökt o tänkt om angående ordern gjort så att den är anpassad till users lagt in det mesta i sessionStorage istället för local. Sluta skriva mina "test" variabler här o där. Sen absolut delat upp min kod mycket mer känner att jag var sjukt dålig på det att återanvända saker och lägga det i egna js filer. adminPage.js är ett exemepel på det där jag har en user/admin/ejinloggad checkning den skulle vara bra o ha i en helt egen js fil.


#### Om ni hade en vecka till på er, vad skulle du ändrat? Fokusera på arbetsprocessen, samarbetet eller verktygen ni använde. Hur skulle det ha påverkat resultatet?

Tror vi skulle kunnat fokuserat mycket mer på users själva samt responsiviteten. Jag hade gjort så varje användare har sin egna orderhistorik och att du har en för alla ordrar som någonsin kommit in. samarbetet verktygen arbetsprocessen allt detta var bra vi hade bra dialog och allt. Vi hade 100% fått en mer klar produkt och välgjord med en vecka till. Skulle vi göra om projetet är jag ganska säker på att vi hade lagt upp det snyggare och varit mer effektiva och skapat mer tasks för alla större delar.
(insert answer here...)

#### Om ni hade en vecka till på er, vad skulle du ändrat? Fokusera på arbetsprocessen, samarbetet eller verktygen ni använde. Hur skulle det ha påverkat resultatet?

(insert answer here...)
