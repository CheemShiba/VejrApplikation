# VejrApplikation
Programmet skal nu udvides, så cirklens bevægelse tager højde for vindhastigheden og ikke kun retningen, så temperaturen vises i vinduet, og så vejrsituationen (skyet, skyfrit...) vises med et ikon.

Afslut funktionen calcWeather med at skalere (forstørre eller formindske) vindvektoren i forhold til den aktuelle vindstyrke. Brug metoden mult på vektoren wind (lige som add) til at skalere vektoren med værdien af windmag.
Indsæt i funktionen draw endnu et kald til funktionen text, som placerer en tekst med y-værdi 100 i stedet for 50. Indholdet af teksten skal være temperaturen i grader celsius, som hentes fra datafilen på samme måde som wind_degree.
Opret endnu et JSONObject til objektet condition i datafilen. Hent herfra strengen "icon", som er en URL til ikonets placering. Brug funktionen loadImage til at indlæse ikonet (sæt "http:" foran URL'en), og brug funktionen image til at vise billedet.
