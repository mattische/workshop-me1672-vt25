# User Stories för att utveckla en enkel hemsida

## Exempel på kravspecifikation: Enkel hemsida

**Kravspecifikation för en enkel hemsida:**
- Hemsidan ska ha fyra sidor: Home (index), About, Contact och Projects
- Designen ska vara responsiv och fungera på olika enheter
- Innehållet ska vara lättläst och tydligt strukturerat
- Kontaktformuläret ska vara funktionellt och skicka meddelanden
- Projektsidan ska visa en portfölj av tidigare arbeten
- Hemsidan ska ha enhetlig navigation mellan alla sidor

## Steg för att skapa en User Story

1. **Identifiera användaren/aktören**
   * Vem kommer att interagera med hemsidan?

2. **Definiera vad användaren vill uppnå**
   * Vilken funktionalitet eller information eftersöker de?

3. **Förstå värdet eller motivet**
   * Varför är detta viktigt för användaren?

4. **Formatera enligt standardmall**
   * "Som [roll] vill jag [funktion/handling] så att [värde/nytta]"

## Exempel på en första User Story

"Som besökare vill jag ha en tydlig navigationsmeny på alla sidor så att jag enkelt kan navigera mellan olika delar av hemsidan utan att använda webbläsarens bakåtknapp."

## Steg för att skapa flera User Stories

1. **Identifiera olika intressenter**
   * Besökare (nya och återkommande)
   * Potentiella kunder
   * Hemsideägaren/administratören

2. **Identifiera olika delar av hemsidan**
   * Startsida
   * About-sida
   * Kontaktsida
   * Projektsida

3. **Identifiera olika funktionaliteter**
   * Navigation
   * Informationsvisning
   * Kommunikation
   * Responsivitet

4. **Skapa user stories för varje kombination**

## Exempel på fler User Stories för hemsideutveckling

1. "Som förstagångsbesökare vill jag direkt på startsidan förstå vad hemsidan handlar om så att jag snabbt kan avgöra om innehållet är relevant för mig."

2. "Som potentiell kund vill jag kunna läsa om personerna bakom företaget på About-sidan så att jag kan bygga förtroende för verksamheten."

3. "Som intresserad besökare vill jag kunna fylla i ett kontaktformulär så att jag enkelt kan ställa frågor utan att behöva öppna mitt e-postprogram."

4. "Som rekryterare vill jag kunna se tidigare projekt med beskrivningar och bilder så att jag kan bedöma kvaliteten på utfört arbete."

5. "Som administratör vill jag enkelt kunna uppdatera projektportföljen så att hemsidan alltid visar aktuella arbeten."

6. "Som mobil användare vill jag att hemsidan anpassar sig till min skärmstorlek så att jag får en bra användarupplevelse oavsett enhet."

## Nedbrytning av User Stories till uppgifter/tasks

För att bryta ner user stories till konkreta uppgifter:

1. **Analysera varje user story**
   * Vilka tekniska komponenter behövs?
   * Vilket innehåll krävs?

2. **Identifiera acceptanskriterier**
   * När anses funktionaliteten vara klar?
   * Hur testar vi att den uppfyller kraven?

3. **Bryt ner i konkreta arbetsuppgifter**
   * Kodning
   * Design
   * Innehållsskapande
   * Testning

4. **Prioritera uppgifterna**
   * Must have
   * Should have
   * Could have
   * Won't have (denna gång)

## Exempel på nedbrytning av User Story till Tasks

User Story: "Som intresserad besökare vill jag kunna fylla i ett kontaktformulär så att jag enkelt kan ställa frågor utan att behöva öppna mitt e-postprogram."

Tasks:
1. Skapa HTML-struktur för kontaktformuläret med fält för namn, e-post, ämne och meddelande
2. Implementera CSS-styling för formuläret som matchar resten av hemsidan
3. Skapa valideringsfunktioner för att säkerställa att alla obligatoriska fält är ifyllda
4. Implementera e-postvalidering för att kontrollera giltigt format
5. Skapa backend-skript för att hantera formulärinlämningar (PHP eller JavaScript)
6. Konfigurera e-postaviseringar till administratören när nya formulär skickas in
7. Skapa en bekräftelsesida eller meddelande som visas efter lyckad inlämning
8. Implementera felhantering och visa användarvänliga felmeddelanden
9. Testa formuläret i olika webbläsare och enheter
10. Implementera skydd mot spam (t.ex. CAPTCHA eller honeypot)

## Ett annat exempel på nedbrytning

User Story: "Som rekryterare vill jag kunna se tidigare projekt med beskrivningar och bilder så att jag kan bedöma kvaliteten på utfört arbete."

Tasks:
1. Skapa en databas/struktur för att lagra projektinformation (titel, beskrivning, bilder, tekniker)
2. Designa layout för projektöversiktssidan som visar alla projekt
3. Skapa layout för enskilda projektdetaljsidor
4. Implementera HTML-struktur för projektöversikten
5. Implementera CSS för projektkort och bildgalleri
6. Skapa funktion för att kategorisera projekt (t.ex. webbdesign, grafisk design)
7. Implementera filtrering baserat på kategorier
8. Optimera bildstorlekar för snabb laddning
9. Implementera lightbox-funktion för att visa bilder i större format
10. Skapa responsiv design för projektvisning på mobila enheter
11. Lägga in testdata med exempel på projekt
12. Testa navigering mellan projektöversikt och detaljsidor
