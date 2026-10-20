
# 🌪️ Oefenmateriaal: Chaotische Lijsten

Als docent kun je deze "slechte" administraties op het bord projecteren of uitdelen. Ze zitten vol met de klassieke fouten die mensen in Excel maken. Dit is perfect om klassikaal te bespreken en de studenten te laten nadenken over hoe ze dit in nette tabellen (Entiteiten) kunnen opsplitsen.

---

## Oefening 1: De Ledenlijst van de Sportclub
*Context: De penningmeester van de lokale tennisclub houdt de leden bij in één groot Excel-bestand. Er gaat van alles mis met de post en contributies.*

| LidNr | Naam | Adres | Telefoon | Sporten | Trainer | Betaald |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Jan de Vries | Kerkstraat 1, Amsterdam | 0612345678 | Tennis, Padel | Henk | Ja |
| 2 | Sanne & Peter Jansen | Dorpsweg 5, A'dam | (leeg) | Padel | Henk & Ingrid | Nee |
| 3 | M. Pietersen | kerkstr. 12, amsterdam | 020-123456 | Tennis | Henk | Ja |
| 4 | Jan de V. | Kerkstraat 1 A'dam | 06-12345678 | Squash | (leeg) | Ja |
---

## Oefening 2: IT Inventarisatie (Bedrijfsapparatuur)
*Context: Een bedrijf houdt bij wie welke laptop of monitor heeft. Als een medewerker van afdeling wisselt, moeten ze dit overal handmatig aanpassen.*

| Apparaat_ID | Soort | Merk | Model | Medewerker | Afdeling | Locatie |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 101 | Laptop | HP | EliteBook | Sarah de Jong | HR | Kantoor 2 |
| 102 | Monitor | Dell | 27 inch | S. de Jong | Human Resources | Kantoor 2 |
| 103 | Laptop | HP | Elitebook | Tom Visser | IT | Kantoor 5 |
| 104 | Muis | Logitech | MX Master | (leeg) | IT | Kantoor 5 (Kast) |
| 105 | Telefoon | Apple | iPhone 13 | Tom | Informatie Tech | Thuiswerkplek |

---

## Oefening 3: Bestellingen in de Schoolkantine
*Context: De kantinejuffrouw typt de bestellingen snel achter elkaar in haar systeem. De kok snapt er in de keuken niks meer van.*

| Bestel_Datum | Student | Klas | Bestelling | Sauzen | Totaalbedrag |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 12-04-2023 | Kevin | 3A | Gezond, Kroket, Fanta | Mayo, Ketchup | 8,50 |
| 12-04-23 | Ali | 3a | Kaasbroodje | Boter | 2,50 |
| 13-04-2023 | K. | 3A | Frikandel | Mayo | 2,00 |

---

## Oefening 4: Scooterwerkplaats "De Snelle Cilinder"

### 📖 De Bedrijfscontext
*Context: Mohammed ('Mo') runt samen met stagiair Sam een scooterwerkplaats in Amsterdam. Klanten brengen hun scooter langs voor reparaties of een onderhoudsbeurt. 

Mo houdt alle reparaties bij in één simpel Excel-bestand. Maar doordat vaste klanten soms meerdere scooters hebben, dezelfde scooters vaker terugkomen en de namen van de monteurs steeds opnieuw worden ingetypt, ontstaat er een hoop dubbele data (duplicaten). Mo wil dit Excel-bestand laten ombouwen naar een nette database van **precies 4 tabellen**.

### 📊 Het Excel-bestand (`reparaties_oktober.xlsx`)

| BonNr | Datum | Klantnaam | Telefoon | Woonplaats | Kenteken | Scooter (Merk/Model) | Klacht / Reparatie | Kosten | Monteur | Betaald? |
| :---: | :---: | :--- | :--- | :--- | :---: | :--- | :--- | :---: | :---: | :---: |
| **101** | 14-10-2026 | Dylan Bakker | 06-11223344 | Amsterdam | D-123-AB | Piaggio Zip | Startmotor vervangen | € 85,00 | Mo | Ja |
| **102** | 15-10-2026 | D. Bakker | 0611223344 | Amsterdam | 45-FGH-1 | Vespa Sprint | Koplamp doorgebrand | € 35,00 | Sam | Nee |
| **103** | 16-10-2026 | Anouk de Wit | 06-99887766 | Diemen | F-991-BB | Sym Mio 50 | Lekke achterband | € 25,00 | Mo | Ja |
| **104** | 18-10-2026 | Kevin Smit | 023-5544332 | Haarlem | DJ-44-K | Piaggio Zip SP | Grote onderhoudsbeurt | € 120,00 | Sam | Ja |
| **105** | 19-10-2026 | Dylan Bakker | 06-11223344 | Amsterdam | D-123-AB | Piaggio Zip | Remkabel gebroken | € 45,00 | Mo | Nee |


---
