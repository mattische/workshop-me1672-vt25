# Use Cases för en enkel hemsida



## Översikt
Här försöker jag beskriva use cases (användarfall) för en enkel hemsida med fyra sidor: 
Home (index), About, Contact och Projects, alltså från tidigare exempel med user stories för en hemsida.

Use cases beskriver interaktionen mellan användare och systemet för att uppnå specifika mål.

Mer om Use Cases;

- https://www.atlassian.com/agile/requirements-management/user-cases
- https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/usability-evaluation



## Aktörer (actors)
- **Besökare**: Personer som besöker hemsidan för information
- **Potentiell kund**: Personer som överväger att anlita företaget
- **Rekryterare**: Personer som utvärderar kompetens för anställning
- **Administratör**: Person som ansvarar för att uppdatera hemsidan

## Use Case 1: Navigera hemsidan

**Aktör**: Besökare

**Beskrivning**: Användaren navigerar mellan olika sidor på hemsidan

**Huvudflöde**:
1. Användaren anländer till hemsidans startsida
2. Användaren ser navigationsmeny med länkar till alla sidor
3. Användaren klickar på en länk i navigationsmenyn
4. Systemet visar den valda sidan
5. Användaren ser samma navigationsmeny på den nya sidan
6. Användaren fortsätter att navigera genom att klicka på andra länkar

**Alternativa flöden**:
- A1: Användaren använder mobilenhet
  1. Systemet visar en anpassad, kompakt meny för mindre skärmar
  2. Användaren klickar på hamburgermenyn för att expandera navigationsalternativen
  3. Fortsätter från steg 3 i huvudflödet

**Förutsättningar**: Hemsidan är tillgänglig och fungerar korrekt

**Eftervillkor**: Användaren har hittat önskad information på hemsidan

## Use Case 2: Kontakta företaget via formulär

**Aktör**: Potentiell kund

**Beskrivning**: Användaren skickar ett meddelande via kontaktformuläret

**Huvudflöde**:
1. Användaren navigerar till Contact-sidan
2. Systemet visar ett kontaktformulär med fält för namn, e-post, ämne och meddelande
3. Användaren fyller i alla obligatoriska fält
4. Användaren klickar på "Skicka"-knappen
5. Systemet validerar att alla fält är korrekt ifyllda
6. Systemet skickar meddelandet och visar en bekräftelse
7. Systemet skickar en notifikation till administratören

**Alternativa flöden**:
- A1: Ofullständigt eller felaktigt ifyllda fält
  1. Efter steg 4, systemet markerar felaktiga fält med ett felmeddelande
  2. Användaren korrigerar felen
  3. Fortsätter från steg 4 i huvudflödet
- A2: Systemfel vid skickande
  1. Efter steg 5, systemet kan inte skicka meddelandet
  2. Systemet visar ett felmeddelande med alternativ kontaktinformation
  3. Användaren noteras om att försöka igen senare

**Förutsättningar**: Kontaktsidan och formuläret fungerar korrekt

**Eftervillkor**: Meddelandet är skickat och administratören notifierad

## Use Case 3: Utforska projektportföljen

**Aktör**: Rekryterare

**Beskrivning**: Användaren utforskar tidigare projekt för att bedöma kvalitet och kompetens

**Huvudflöde**:
1. Användaren navigerar till Projects-sidan
2. Systemet visar en översikt av alla projekt med miniatyrbilder och korta beskrivningar
3. Användaren ser filtreringsalternativ för olika projektkategorier
4. Användaren väljer en kategori för filtrering
5. Systemet visar enbart projekt inom den valda kategorin
6. Användaren klickar på ett specifikt projekt
7. Systemet visar en detaljerad projektsida med fler bilder och information
8. Användaren kan navigera mellan projekten eller tillbaka till översikten

**Alternativa flöden**:
- A1: Användaren använder sökfunktion
  1. Efter steg 2, användaren skriver sökord i sökfältet
  2. Systemet visar projekt som matchar sökningen
  3. Fortsätter från steg 6 i huvudflödet

**Förutsättningar**: Projektsidan är tillgänglig och innehåller projektdata

**Eftervillkor**: Användaren har fått information om tidigare projekt

## Use Case 4: Lära om företaget

**Aktör**: Potentiell kund

**Beskrivning**: Användaren inhämtar information om företaget och dess personal

**Huvudflöde**:
1. Användaren navigerar till About-sidan
2. Systemet visar information om företagets historia, vision och värderingar
3. Användaren scrollar nedåt för att se teammedlemmar
4. Systemet visar bilder och beskrivningar av nyckelpersoner
5. Användaren klickar på en teammedlems profil
6. Systemet visar utökad information om personen
7. Användaren kan navigera tillbaka till huvudsektionen eller andra sidor

**Förutsättningar**: About-sidan är tillgänglig med aktuell information

**Eftervillkor**: Användaren har fått kunskap om företaget och dess personal

## Use Case 5: Uppdatera projektportföljen

**Aktör**: Administratör

**Beskrivning**: Administratören lägger till eller uppdaterar projekt i portföljen

**Huvudflöde**:
1. Administratören loggar in på administratörspanelen
2. Systemet visar en översikt av befintliga projekt
3. Administratören väljer "Lägg till nytt projekt"
4. Systemet visar ett formulär för projektinformation
5. Administratören fyller i projektinformation och laddar upp bilder
6. Administratören väljer projektkategori och taggar
7. Administratören förhandsgranskar projektet
8. Administratören publicerar projektet
9. Systemet lägger till projektet i portföljen

**Alternativa flöden**:
- A1: Uppdatera befintligt projekt
  1. Efter steg 2, administratören väljer ett befintligt projekt
  2. Systemet visar projektets information i ett redigerbart formulär
  3. Administratören gör ändringar
  4. Fortsätter från steg 7 i huvudflöden
- A2: Ta bort projekt
  1. Efter steg 2, administratören väljer att ta bort ett projekt
  2. Systemet begär bekräftelse
  3. Administratören bekräftar borttagning
  4. Systemet tar bort projektet från portföljen

**Förutsättningar**: Administratören har inloggningsuppgifter och behörighet

**Eftervillkor**: Projektportföljen är uppdaterad med aktuell information

## Use Case 6: Anpassa visning för olika enheter

**Aktör**: Besökare

**Beskrivning**: Hemsidan anpassar sig automatiskt till användarens enhet

**Huvudflöde**:
1. Användaren besöker hemsidan från en mobil enhet
2. Systemet identifierar skärmstorleken
3. Systemet anpassar layouten för optimal visning på den enheten
4. Bilder skalas och laddas i lämplig storlek för enheten
5. Navigationsmeny visas i ett format anpassat för mobilen
6. Användaren kan navigera och interagera med innehållet anpassat för enheten

**Alternativa flöden**:
- A1: Användaren roterar enheten
  1. Systemet detekterar orienteringsändringen
  2. Layouten anpassas för det nya visningsläget
- A2: Användaren byter till en annan enhet
  1. Systemet identifierar den nya enheten
  2. Innehållet anpassas för den nya skärmstorleken

**Förutsättningar**: Hemsidan är byggd med responsiv design

**Eftervillkor**: Användaren har en optimal användarupplevelse oavsett enhet
