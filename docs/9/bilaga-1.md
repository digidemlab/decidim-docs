---
title: "📎 Bilaga 1 (instruktion)"
layout: default
parent: "👀 PUB-avtalet"
grand_parent: "✌🏼 Kom igång med din plattform"
has_children: false
has_toc: false
nav_order: 1

---
# Bilaga 1: Instruktion för behandling av personuppgifter

Utöver vad som redan framgår av detta avtal ska Personuppgiftsbiträdet även följa nedanstående instruktioner:

## 1. Ändamål, föremålet och arten

Personuppgifterna behandlas för följande ändamål:
- för att fullgöra Huvudavtalet
- för att fullgöra övriga skyldigheter som åvilar Personuppgiftsbiträdet enligt Huvudavtalet och detta Personuppgiftsbiträdesavtal

**[Här kan man även beskriva mer dialogprocesserna som kommer ske på plattformen och hur de kommer involvera användarna för att bidra till organisationens mål]**

## 2. Kategorier av personuppgifter

Följande kategorier kan förekomma i behandlingen av personuppgifter.
- **E-postadress** (nödvändigt)
- **Användarnamn** (nödvändigt)
- **Lösenord** (nödvändigt)

Utöver detta kan vi samla de följande demografiska personuppgifter (ta bort om inte relevant):
- **Åldersgrupp** (frivilligt)
- **Kön** (frivilligt)
- **Boendesområde** (frivilligt)

Eftersom Decidims användare kan skapa innehåll (förslag, enkätsvar, kommentarer osv.) och skriva vad som helst kan det förekomma andra typer av personuppgifter, t.ex.:
- **Födelseår**, i de fall dessa ingår i förslagstext/e- postadresser
- **Hemadresser** i de fall de refereras till i förslagstext
- **Information om hälsotillstånd** och annat personbundet om
detta refereras till i förslagstext
- **Kön**
- **Boendeområde**

Personuppgiftsbiträdet även sparar **besöksstatistik** för webbsidan.

## 3. Kategorier av registrerade

- **Enskilda användare:** medborgare, hyresgäster, elever (välj det som passar i kontexten)
- **Enskilda administratörer:** tjänstepersoner, anställda
- **Enskilda anställda hos personuppgiftsbiträdet och hos andra leverantörer** som använder eller driver plattformen.

## 4. Praktisk hantering

| Behandlingssteg | Beskrivning |
| ----------- | ----------- |
| Insamling   | Se 1. för en full lista av insamlade personuppgifter. Besöksstatistik görs med verktyget Matomo på ett anonymt sätt. Allt annat data samlas när användarna skapar sitt konto eller när de skapar offentligt innehåll på plattformen.       |
| Överföring och lagring | Datan används inte utanför plattformen och lagras på våra egna servrar (se 7.) |
| Analys   | Aggregerade data kan analyseras i form av visualiseringar och anonym statistik kan exporteras för vidare analys utanför verktyget |
| Administration   | Plattformens administratörer får endast tillgång till användarnas e-postadress och till aggregerade anonyma statistik av vissa andra personuppgifter (kön, åldersgrupp) |

## 5. Särskilda säkerhetskrav

- Kryptering av all data som skickas från och till användarens dator så den kan inte bli avlyssnad.
- Alla lösenord är "hashade och saltade" så de inte sparas i databasen.
- Besöksstatistiken samlas med verktyget Matomo som drivs på egen server. Alla statistik är anonymiserade.
- Loggar samlas med verktyget Sentry som drivs på egen server. Loggar innehåller i princip inga personuppgifter.
- Uppgifterna som åldersgrupp, boendeområde och kön är krypterade i databasen och de val man får är stora kategorier som gör det svårare att identifiera användaren.
- För att minska risken att förlora data gör personuppgiftsbiträdet dagliga backups av serverns innehåll.

## 6. Loggar

Alla administratörers åtgärder registreras i en logg som är tillgänglig till alla andra administratörer i admin-panelen. Detta logg innehåller även åtgärderna som rör användarnas personuppgifter.

För att kunna upptäcka tekniska fel snabbt och effektivt använder personuppgiftsbiträdet verktyget Sentry på egen server. Sentry sparar felloggar för plattformen.

## 7. Överföring av personuppgifter till tredje land

Behandlingen av personuppgifter sker endast i EU/EES.

- Plattformen driver från en server hos Hetzner i **Finland**
- Besöksstatistik samlas på en Matomo server hos Hetzner i **Finland**
- Loggar samlas på en Sentry server hos Hetzner i **Finland**
- Mejlen som skickas av plattformen skickas igenom tjänsten Emaillabs, på servrar i **Polen**

Läs mer om våra underbiträden i [bilagan 2](bilaga-2).

## 8. Gallringstid

Personuppgifterna och säkerhetskopior sparas till projektet är slut eller enligt huvudavtalet.

Efter det kommer personuppgiftsbiträdet återlämna allt data till det personuppgitftansvariga och radera det från sina egna database.
