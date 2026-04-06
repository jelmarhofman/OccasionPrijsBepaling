# OccasionPrijsBepaling

Een standalone HTML-toepassing die de verwachte verkoopprijs van een gebruikte auto berekent.

## Gebruik

Open `Occasion_prijsmodel_Jelmar.html` in een webbrowser. Er is geen installatie of server nodig.

## Invoervelden

| Veld | Omschrijving |
|---|---|
| Merk / Model | Naam van het voertuig (informatief) |
| Bouwjaar | Productiejaar van de auto |
| Catalogusprijs | Nieuwprijs van het voertuig in euro's |
| Kilometerstand | Totaal gereden kilometers |
| Brandstof | Benzine, Diesel, Elektrisch, Hybride of LPG |
| Carrosserie | Hatchback, Sedan, Stationwagon, SUV, Coupé, MPV of Cabrio |
| Transmissie | Handgeschakeld of Automaat |
| Staat | Schuifregelaar van Slecht (1) tot Uitstekend (5) |

## Berekeningsmodel

1. **Leeftijdsafschrijving** – eerste jaar −20 %, daarna −10 % per jaar (minimum 15 % van catalogusprijs).
2. **Kilometerafschrijving** – −1 % per 10 000 km boven 20 000 km (max. −25 %).
3. **Conditiefactor** – Slecht −15 % · Matig −7 % · Goed ±0 % · Zeer goed +5 % · Uitstekend +10 %.
4. **Brandstof- en uitvoeringsfactor** – marktconforme correctie op basis van brandstoftype, carrosserie en transmissie.
