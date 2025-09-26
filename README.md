# Retro Coding Challenge

Ett roligt och utmanande spel där du får resa genom olika epoker av dators historia genom att lösa kodutmaningar. Varje nivå representerar en tidsepok med sin egen stil och programmeringsspråk.

## Nivåer

### 1. DOS Level (`dos.html`)
- **Tema:** Retro DOS-terminal med grön text på svart bakgrund.
- **Utmaning:** Fixa en BASIC/VB-kod som ska runda tal till 2 decimaler. Uppdatera tabellen så att debit och kredit balanserar.
- **Språk:** Fake BASIC med VB-influenser.
- **Mål:** Gör alla tal i verifikationsuträkningen till 2 decimaler genom att använda rätt `SUB FixPrice`.
### DOS Level
![DOS Level](screenshots/1.png)

### 2. Windows 3.11 Level (`311.html`)
- **Tema:** Windows 3.11-fönster med VB IDE.
- **Utmaning:** Fixa VB-kod så att `fullname` blir "Daniel Nilsson" med mellanslag.
- **Språk:** Visual Basic (VB).
- **Mål:** Ändra `fullname = name & lastname` till att inkludera ett mellanslag, så att fakturan uppdateras.
### 3. Windows 3.11 Level
![DOS Level](screenshots/2.png)

### 3. Web 1.0 Level (`webera.html`)
- **Tema:** Internet Explorer 6 med scriptfel-popup.
- **Utmaning:** Fixa JavaScript-kod där arrayerna har olika längd, vilket orsakar ett fel.
- **Språk:** JavaScript.
- **Mål:** Gör alla arrayer lika långa så att fakturan renderas utan fel.
### 3. Web 1.0 Level
![DOS Level](screenshots/3.png)

### 4. Future Level (`future.html`)
- **Tema:** Modern AI-driven betalningsflöde.
- **Utmaning:** Skriv en korrekt prompt med JSON för att skicka en betalning genom AI-validering.
- **Språk:** Naturligt språk + JSON.
- **Mål:** Inkludera rätt IBAN, belopp, valuta och referens för att få "ACCEPTED" från Bank-AI.

## Hur man spelar

1. Öppna `index.html` i din webbläsare (använd en lokal server för bästa upplevelse, t.ex. `python -m http.server`).
2. Spelet startar på Level 1 (DOS).
3. Läs utmaningen och ändra koden i textarea enligt instruktionerna.
4. Klicka på "Kör programmet" eller motsvarande knapp.
5. Om rätt: Gå vidare till nästa nivå automatiskt.
6. Om fel: Försök igen.
7. Klara alla nivåer för att få grattis-meddelande!

## Teknologier
- **HTML/CSS:** För layout och styling av varje epoks tema.
- **JavaScript:** För logik, kodkontroll och nivånavigation.
- **Inspiration:** Retro computing, programmeringshistorik.

## Installation
- Klona eller ladda ner filerna.
- Öppna `index.html` i en modern webbläsare.
- För lokal server: `cd /path/to/project && python3 -m http.server 8000`, öppna `http://localhost:8000/index.html`.

## Bidrag
Detta är ett lekprojekt – känn dig fri att förbättra nivåerna eller lägga till fler! Öppna issues eller pull requests på GitHub om du vill bidra.

## Licens
MIT License – använd fritt för lärande och underhållning.

Ha kul med kodandet genom tiderna! 💾
