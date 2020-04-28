---
layout: default
nav_order: 1
title: "\U0001F195 Skapa en förslagskomponent"
parent: "\U0001F4E5 Förslag"
grand_parent: "\U0001F9F0 Dialogfunktioner"
has_children: false
has_toc: false

---
# 🆕 Skapa en förslagskomponent

För att skapa en förslagskomponent för ditt dialogutrymme får du gå till sin admin-sida och **Komponenter**. Där hittar du en knapp **Lägg till komponent** där du kan välja **Förslag**.

Du kommer på en lång sida med många inställningar. Vi kommer gå igenom var och en av dem.

## Globala inställningar

![]({{ site.url }}/decidim-docs/uploads/proposal-admin-1.png)

 1. **Namn**, komponentens rubrik;
 2. **Vikt**, komponentens position i menyn relativt till de andra;  
      
    ![]({{ site.url }}/decidim-docs/uploads/proposal-admin-2.png)
 3. **Röstningsgräns per användare**, hur många förslag en användare kan rösta på. 0 betyder obegränsat;
 4. **Minsta antal röster per användare**, hur många förslag en användare måste rösta på så sin röst räknas;
 5. **Förslagsgräns per användare**, hur många förslag en användare kan skapa. 0 betyder obegränsat;
 6. **Maximal längd på förslagets innehåll**, hur lång förslagstexten kan vara (antal tecken);
 7. **Förslag kan redigeras av författare inom så här många minuter**, hur lång tid man kan redigera sitt förslag efter man har skapat det;
 8. **Tröskel per förslag**, hur många röster måste förslaget samla för att gå vidare till nästa steg i processen;

    ![]({{ site.url }}/decidim-docs/uploads/proposal-admin-3.png)
 9. **Kan samla in stöd bortom tröskeln**, förslagen kan samla in röster även efter de har nått tröskeln;
10. **Aktiverat svar på förslag**, administratörerna kan och får ge ett svar till förslagen;
11. **Officiella förslag aktiverade**, administratörerna kan skapa officiella förslag;
12. **Kommentarer aktiverade**, förslagen kan kommenteras
13. **Geokodning aktiverad**, aktiverar en karta där alla förslag som har en adress synas;
14. **Tillåt bilagor**, förslagen kan innehålla bilagor (bilder och dokument);
15. **Åtgärdsbehörigheter kan ställas in för varje förslag** (se vår sida om åtgärdsbehörigheter);
16. **Samarbetsutkast aktiverat**, tillåter användarna att skapa förslagsutkast och samarbeta på dem med andra innan de publicerar sitt förslag;
17. **Deltagartexter är aktiverade** (se vår sida om deltagartexter);
18. **Ändringar möjliga** (se vår sida om deltagartexter);

    ![]({{ site.url }}/decidim-docs/uploads/proposal-admin-4.png)
19. **Meddelande**, en text som kommer visas ovanpå listan av förslag;
20. **Hjälptexter**, olika hjälptexter som kommer att visas när användaren skapar sitt förslag.

## Fasinställningar

Om du använder komponenten i en process finns det fler inställningar för att konfigurera komponentens beteende under de olika faserna.

![]({{ site.url }}/decidim-docs/uploads/proposal-admin-5.png)

 1. **Instämmanden aktiverade**, användarna kan ge sitt instämmande till ett förslag och se antalet instämmanden;
 2. **Instämmanden är blockerade**, användarna kan inte ge fler instämmanden (men kan se dem om **1** är aktiverad);
 3. **Röstning aktiverat**, användarna kan stötta ett förslag och se antalet stöder;
 4. **Röstande blockerat**, användarna kan inte ge fler röster (men kan se dem om 3 är aktiverad och 5 avaktiverad);
 5. **Röster dolda**, gömmer antalet röster;
 6. **Kommentarer blockerade**, kommentarer blockeras under den här fasen;
 7. **Skapande av förslag aktiverat**, användarna kan skapa förslag;
 8. **Svar på förslag aktiverat**, administratörerna kan svara till förslagen;

      
    ![]({{ site.url }}/decidim-docs/uploads/proposal-admin-6.png)
 9. **Meddelande**, en text som kommer visas ovanpå listan av förslag under den här fasen;
10. **Hashtags läggs till i alla förslag**
11. **Förslag på hashtags för nya förslag till deltagare**