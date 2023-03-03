# Inloggningssystem | wsp1  | Post Mortem 


## Inledning
I detta projekt så har jag och min grupp skapat en hemsida där man kan logga in med hjälp av en mysql databas. I detta projekt så skapades hemsidan med olika routers och views. För att göra sin profil sida säker på hemsidan så använde vi oss av en session. Sedan skapade vi också en sida där man kan registrera nya användare och en sida för att ta bort användare.

## Bakgrund
mysql är en databas där man kan spara information. Denna information kan användas till många olika typer av hemsidor men till våran uppgift så användes den till att logga in. Med hjälp av mysql så kan vi logga in på ett lätt och säkert sätt. Men vi kan också ta bort en användare från databasen om användaren vill. Vi har kunnat skapa hela projektet med hjälp av routes och views. Views är kopplad till routes, views är själva html koden medans routes är där man skriver javascript kod för att kunna till exempel logga in eller registrera en egen användare. För att göra inloggningen säker så använde vi oss av hash kod, då avändes bcrypt. Den kan man använda för att skapa hash och för att jämföra om lösenordet är likadant med hash koden. Det gör att lösernordet blir mycket säkrare än att spara lösenordet som string.

## Positiva erfarenheter
Jag tyckte uppgiften gick bra efter dem två första lektionerna. Då började man förstå hur allting fungerade med testerna och koden. Detta gjorde att man kunde ha en bättre dialog med klasskamraterna. Jag tyckte grupparbetet var en bra erfarenhet för att den fungerade på ett bra sätt. Sedan har jag lärt mig en hel del om hur routes och mysql fungerar.

## Negativa erfarenheter
Jag tyckte det gick lite dåligt i början av projektet därför det var lite svårt att förstå testerna. Detta är en sak som förbättrades efter varje lektion men man skulle kunnat ha fått en förklaring över hur testerna fungerar. 

## Sammanfattning
Som sammanfattning tycker jag att detta sätt att arbeta var ett mycket bra sätt. Det var lite segt i början men så kan det vara med dem flesta arbeterna. Men annars tycker jag arbetet i överlag var ett bra projekt och jag tycker jag har lärt mig mycket. 