# inlamningsuppgift-1

## Instruktioner
I denna inlämningsuppgift ska du bygga en Node.JS-applikation för en e-handelssida. Du ska skapa upp ett API samt en databas med lowdb som ska hantera din e-handelssida. 

**Avgränsning**

Denna inlämningsuppgift ska inte ha någon HTML, CSS eller JavaScript (i klienten). Utan det kommer i nästa inlämningsuppgift där du ska använda dig av ditt API från denna uppgift.

### Krav på funktionalitet

**Endpoints för följande funktionalitet:**
* Hämta alla produkter för att visa på en produktlistningssida (se nedan på vad en produkt ska innehålla)
* Kunna lägga till en produkt i en varukorg
* Kunna ta bort en produkt i en varukorg
* Hämta alla produkter i en varukorg

**Felhantering**
* Man ska inte kunna lägga till samma produkt i varukorgen igen
* Man ska få ett felmeddelande om man försöker lägga till en produkt som inte finns
* Man ska få ett felmeddelande om man försöker ta bort en produkt som inte finns

**En produkt ska innehålla:**
* Namn
* Pris
* En bild url (Använd exempelvis denna sida för att generera bild-url:er https://placeimg.com/)


**Följande ska levereras:**
* Ett API enligt nedan kravspecifikation
* En package.json med alla dependencies som behövs för att köra projektet
* En databas

**Inlämning:** 23/4 senast kl. 23:59
