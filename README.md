## sten sax påse
Här är en enkel övning i C++ för att skapa ett "Sten, Sax, Påse"-spel. Programmet låter användaren spela mot datorn, som gör ett slumpmässigt val. Du kan använda standardbiblioteket <cstdlib> rand() för att generera slumpmässiga nummer.

### 1. Uppgift:

Skriv ett program i C++ som gör följande:
Ber användaren att välja mellan "sten", "sax" eller "påse".
Genererar ett slumpmässigt val för datorn.
Jämför användarens val med datorns och avgör vem som vinner.
Visar resultatet av spelet.

### 2. Lägga till poängräkning

Utöka spelet så att det håller reda på poängen för både användaren och datorn. Låt spelet fortsätta i flera rundor och visa poängställningen efter varje runda. Avsluta spelet när antingen användaren eller datorn når ett visst antal poäng, exempelvis 3 poäng.

Exempel:
Definiera två variabler userScore och computerScore.
Skapa en while-loop som fortsätter spelet tills någon av spelarna når 3 poäng.
Uppdatera poängen för varje runda och visa aktuell ställning.

### 3. Lägga till ett textbaserat användargränssnitt

Skapa ett menybaserat gränssnitt där användaren kan välja olika alternativ:
Starta nytt spel.
Visa statistik.
Avsluta spelet.
Exempel:
Använd en do-while loop för att visa menyn och hantera användarens val.
Implementera funktioner för att visa statistik och starta om spelet utan att avsluta programmet.
